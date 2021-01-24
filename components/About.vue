<template>
  <body class="bg-gradient-to-b from-orange-400 to-red-500">
    <section class="text-gray-600 body-font">
      <div
        class="container mx-auto flex px-5 py-32 items-center justify-center flex-col"
      >
        <img
          class="lg:w-1/4 md:w-4/6 w-1/2 mb-10 object-cover object-center rounded"
          alt="hero"
          src="../static/community.svg"
        />
        <div class="text-center lg:w-2/3 w-full">
          <h1
            class="title-font md:text-5xl text-2xl mb-4 font-medium text-black"
          >
            En iyisi, iyileri. <br />
            Sizin için.
          </h1>
          <p class="mb-8 mt-3 leading-snug text-gray-300">
            Yaz Çiçekleri'nde haftalık düzenenlenen film/müzik/oyun
            etkinlikleriyle, aylık düzenenlenen çekilişler arasında gidip
            gelmeye hiç gerek yok. Bunu bir düzen içerisinde zaten ekipçe
            yapıyoruz. ;) <br />
            Sunucumuza gelmek için altta bulunan "Discord" butonuna tıklayıp,
            kendi <a class="underline">'çiçek'</a> hikayenizi bugünden itibaren
            yazmaya başlayabilirsiniz.
          </p>
          <div class="flex justify-center">
            <a href="https://discord.gg/VvN88r3">
              <button
                class="inline-flex text-white bg-red-500 border-0 py-2 px-6 focus:outline-none hover:bg-red-600 rounded-2xl text-lg hover:underline"
              >
                Discord Topluluğumuz
              </button>
            </a>
          </div>
        </div>
      </div>
    </section>

    <section class="text-gray-600 body-font">
      <div
        class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
      >
        <div
          class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
        >
          <h1
            class="title-font md:text-5xl text-3xl mb-4 font-medium text-black"
          >
            Sizlerin
            <a class="underline"
              >memnuniyetini, <br class="hidden lg:inline-block" />
              güvenliğini</a
            >
            bizzat önemseriz.
          </h1>
          <p class="mb-8 mt-6 leading-relaxed text-gray-300">
            Sunucumuzda bulunduğunuz süre zaafında kurallara uymayan herhangi
            birisi size; sataşıyorsa, kavga ortamı oluşturmaya müsaitse,
            herhangi bir neden ötürü ne olursa olsun sizi bile bile rahatsız
            ediyorsa biz buradayız. <br> Arsa Bekçilerine bu terbiyesiz tohumları
            şikayet edip, adaleti <strong>siz</strong> sağlayabilirsiniz bizzat
            bize bu bahsettiğimiz etkenleri yapan kullanıcıların adlarını ve
            ID'lerini özelden ulaştırırsanız.
          </p>
        </div>
        <div class="lg:max-w-lg lg:w-full md:w-4/6 w-1/2">
          <img
            class="object-cover object-center rounded"
            alt="hero"
            src="../static/secure-shield.svg"
          />
        </div>
      </div>
    </section>

    <section class="text-gray-600 body-font">
      <div
        class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
      >
        <div class="lg:max-w-lg lg:w-full md:w-4/6 w-1/2 mb-10 md:mb-0">
          <img
            class="object-cover object-center rounded"
            alt="hero"
            src="../static/game-controller.svg"
          />
        </div>
        <div
          class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center"
        >
          <h1
            class="title-font md:text-5xl text-3xl mb-4 font-medium text-black"
          >
            Sunucu içerisinde olan
            <a class="underline">eğlenceli oyunlar ile</a> kendi seviyenizi bir
            üstte taşıyın.
          </h1>
          <p class="mb-8 mt-6 leading-snug text-gray-300">
            Sunucumuzda bulunan eğlenceli kelime oyunları, tuttu-tutmadı,
            vampir-köylü gibi oyunlarla hem seviyeniz için XP kazanabilir, hem
            arkadaşlarınızla beraber ortak bir şekilde oyununuzu
            oynayabilirsiniz. Merak etmeyin, vampir olduğumuz zaman sizi zevk
            diye ısırmayacağız ama bunun garantisini hiçbir yetkili ekip üyesi
            sağlayamaz. 😈
          </p>
        </div>
      </div>
    </section>

    <section class="text-gray-600 body-font">
      <div class="container px-5 py-24 mx-auto">
        <div class="flex flex-col text-center w-full mb-12">
          <h1
            class="sm:text-3xl text-2xl font-medium title-font mb-2 text-black"
          >
            Ne duruyorsunuz?! Bizde çay için sizi bekliyorduk. 😠
          </h1>
          <p class="lg:w-2/3 mx-auto leading-relaxed text-gray-300">
            Şaka bir yana, sizleri de sunucumuzda karşılamaktan gurur duyarız.
            Haydi! Aşağıda bulunan sihirli butona tıklayarak; yine sihirli bir şekilde 
            Discord topluluğumuza katılabilirsiniz, bu heyecanlı olacak gibi duruyor.
          </p>
        </div>
        <div
          class="flex lg:w-2/3 w-full sm:flex-row flex-col mx-auto px-8 sm:space-x-4 sm:space-y-0 space-y-4 sm:px-0 items-end"
        >
          <button
            class="widthius text-white bg-orange-500 border-0 py-2 px-5 focus:outline-none hover:bg-orange-600 hover:underline rounded-2xl text-lg"
          >
            <a href="https://discord.gg/VvN88r3">Sunucuya Katıl!</a>
          </button>
        </div>
      </div>
    </section>
  </body>
</template>

<style>
.widthius {
  margin: 0 auto;
}
</style>
