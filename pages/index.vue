<template>
  <div>
  <Header />

    <div class="bg-gray-100 ">
      <img src="~/assets/slide1.png" alt="">
      <div class="container flex w-8/12 mx-auto">
        <div class="w-4/12 p-2 ">
          <div class=" p-6  bg-cyan-50 ">
                <div class="flex justify-center items-center ">
                  <img src="~/assets/nargiza.jpg" width="100%" alt="">
                </div>
                <div class="my-4  border-l-4  border-red-500">
                    <h4 class="mx-5 mb-4">Xidoyatova Nargiza Sadikjonovna</h4>
                    <p class="mx-5 text-sm">Toshkent shahar Yunusobod tuman 5-son umumta'lim maktabi direktori</p>
                </div>
            <hr>
            <div class="my-4">
              <fa :icon="['fa', 'rss']"/>
              xchnbkjxbkj
            </div>



          </div>
        </div>
        <div class="w-8/12 py-2 ">
          <div class="border bg-white">
            <div class="w-11/12 mx-auto p-5">
            <h1 class="my-6 mx-5">Yangiliklar</h1>
            <hr>
            <div class="flex mt-4 mb-2"  v-for="(item,index) in news " :key="item.index">
              <div class="w-3/12 mx-3 mt-3 border rounded-lg">
                <img src="~/assets/prava.jpeg" alt="">
                <h5 class="flex rounded-b-lg justify-center items-center text-white text-sm bg-slate-700">
                  Yangiliklar
                </h5>
              </div>
              <div class="w-8/12 p-1 inline-block">
                <h4 class="text-base text-blue-500">
                    <nuxt-link to="">
                    {{item.title}}
<!--                      Xalq ta’limi vazirligi 16 yoshga to‘lgan maktab bitiruvchilaridan o‘z vaqtida pasport (id karta) olishni so‘raydi-->
                    </nuxt-link>
                </h4>
                  <p class="text-xs mt-2">
                    {{item.text}}
<!--                    Oliy ta’lim muassasalariga abituriyentlarning hujjatlari Davlat test markazining abitur.dtm.uz sayti orqali onlayn qabul qilinadi. Abituriyentlar endi avvalgidek oliy ta’lim muassasalariga ovora bo‘lib borishlari, uzundan-uzoq navbatga turishlariga...-->
                  </p>
                  <ul class="flex items-center">
                    <li class="text-xs p-2">{{item.date}}</li>
                    <li class="text-base p-2 text-blue-500"><fa :icon="['fas', 'download']"/> <a href="" class=" underline"> Batafsil</a></li>
                  </ul>
              </div>
              <hr>

            </div>

            </div>
            </div>
          </div>
        </div>
      </div>



  <Footer />
</div>
</template>

<script>
export default {
  name: 'IndexPage',
  data(){
    return {
      news:[
        {'id': 1,
          'title': ' Xalq ta’limi vazirligi 16 yoshga to‘lgan maktab bitiruvchilaridan o‘z vaqtida pasport (id karta) olishni so‘raydi',
          'text': 'Oliy ta’lim muassasalariga abituriyentlarning hujjatlari Davlat test markazining abitur.dtm.uz sayti orqali onlayn qabul qilinadi. Abituriyentlar endi avvalgidek oliy ta’lim muassasalariga ovora bo‘lib borishlari, uzundan-uzoq navbatga turishlariga...',
          'date': '29.03.2022 / 08:37'
        },
        {'id': 2,
          'title': ' Xalq ta’limi vazirligi 16 yoshga to‘lgan maktab bitiruvchilaridan o‘z vaqtida pasport (id karta) olishni so‘raydi',
          'text': 'Oliy ta’lim muassasalariga abituriyentlarning hujjatlari Davlat test markazining abitur.dtm.uz sayti orqali onlayn qabul qilinadi. Abituriyentlar endi avvalgidek oliy ta’lim muassasalariga ovora bo‘lib borishlari, uzundan-uzoq navbatga turishlariga...',
          'date': '29.03.2022 / 08:37'
        },
        {'id': 3,
          'title': ' Xalq ta’limi vazirligi 16 yoshga to‘lgan maktab bitiruvchilaridan o‘z vaqtida pasport (id karta) olishni so‘raydi',
          'text': 'Oliy ta’lim muassasalariga abituriyentlarning hujjatlari Davlat test markazining abitur.dtm.uz sayti orqali onlayn qabul qilinadi. Abituriyentlar endi avvalgidek oliy ta’lim muassasalariga ovora bo‘lib borishlari, uzundan-uzoq navbatga turishlariga...',
          'date': '29.03.2022 / 08:37'
        }
  ]
    }
  }

}
</script>
