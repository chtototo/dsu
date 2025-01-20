<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="main h-[100vh] w-[full] bg-cover bg-center flex flex-col items-center p-3 text-white justify-between pb-8">
    <header class="flex flex-col items-center gap-8 text-xl font-semibold w-full">
      <nav class="flex flex-row gap-4 text-white uppercase">
        <a class="hover:underline" href="/">прием</a>
        <a class="hover:underline" href="/">сведения</a>
        <a class="hover:underline" href="/">галерея</a>
        <a class="hover:underline" href="/">новости</a>
        <a class="hover:underline" href="/">архив</a>
      </nav>
      <div class="w-full grid grid-cols-7 items-center">
        <nav class="col-span-3 flex flex-row text-white">
          <a class="hover:underline w-full text-center" href="/">Университет</a>
          <a class="hover:underline w-full text-center" href="/">Пресса</a>
          <a class="hover:underline w-full text-center" href="/">Наука</a>
          <a class="hover:underline w-full text-center" href="/">Структура</a>
          <a class="hover:underline w-full text-center" href="/">Контакты</a>
        </nav>

        <div class="">
          <a class="justify-self-center cursor-pointer flex flex-col items-center text-white font-semibold" link=/>
            <img src="./images/logo2.png" alt="" width="70" />
            <p>DGU</p>
          </a>
        </div>

        <nav class="col-span-3 flex flex-row text-white">
          <a class="hover:underline w-full text-center" href="/">Образование</a>
          <a class="hover:underline w-full text-center" href="/">Абитуриенту</a>
          <a class="hover:underline w-full text-center" href="/">Студентам</a>
          <a class="hover:underline w-full text-center" href="/">Сотрудникам</a>
          <a class="hover:underline w-full text-center" href="/">Контакты</a>
        </nav>
      </div>
    </header>

    <h1 class="text-7xl text-white font-normal text-center w-5/6">Дагестанский Государственный Университет</h1>

    <a href="#content" class="cursor-pointer hover:text-zinc-300 text-2xl text-center">
      <p>Explore</p>
      <p>↓</p>
    </a>
  </div>

  <main id="content" class="min-h-screen bg-white flex flex-col gap-28 pb-28">
    <div class="w-full bg-indigo-200 p-[10vw] text-4xl">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem nulla labore, amet, dicta, dignissimos dolorem laudantium culpa error iusto dolorum expedita nostrum. Maxime quaerat autem harum, magnam atque eum ipsa.</div>
    <div class="grid grid-cols-3 grid-rows-2 h-screen gap-4 mx-[5vw]">
      <div class="w-full h-full bg-blue-950 rounded-xl row-span-2 bg-[url('./images/dgu.png')] bg-cover bg-center flex flex-col justify-end p-[10%] gap-6 text-white">
        <h3 class="text-4xl">Welcome to the DSU</h3>
        <p class="text-xl">Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis beatae eligendi ex. Eius, expedita iste atque dolorum aspernatur in quae similique sapiente blanditiis exercitationem doloremque officiis, natus modi alias veniam?</p>
        <button class="border-[1px] border-white rounded-3xl w-32 px-4 py-2 hover:bg-white hover:text-black transition-[.1s]">Read More</button>
      </div>
      <div class="w-full h-full bg-blue-950 rounded-xl col-span-2 text-white flex flex-col justify-center gap-6 p-[5%]">
        <h3 class="text-5xl">Arrange a Personal Visit</h3>
        <p class="text-xl">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores velit iure nostrum deleniti illum dicta alias doloremque, aliquid culpa ipsa sit consequatur in rerum quasi sapiente accusantium et, nesciunt aut.</p>
        <button class="border-[1px] border-white rounded-3xl w-32 px-4 py-2 hover:bg-white hover:text-blue-950 transition-[.1s]">Read More</button>
      </div>
      <div class="w-full h-full bg-blue-950 rounded-xl flex justify-center items-center">
        <img src="./images/logo2.png" alt="">
      </div>
      <div class="w-full h-full bg-indigo-200 rounded-xl text-blue-950 flex flex-col justify-center gap-6 p-[10%]">
        <h3 class="text-5xl">Admissions</h3>
        <p class="text-xl">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores velit iure nostrum deleniti illum dicta.</p>
        <button class="border-[1px] border-blue-950 rounded-3xl w-32 px-4 py-2 hover:bg-blue-950 hover:text-indigo-200 transition-[.1s]">Read More</button>
      </div>
    </div>
    <div class="h-[150vh] bg-blue-950 flex flex-col text-white py-[5%] gap-[15%]">
      <div class="flex flex-row justify-between gap-8 h-full items-center">
        <div class="w-full h-full bg-[url('./images/dgu.jpg')] bg-center bg-cover"></div>
        <div class="flex flex-col gap-6 mr-8">
          <h4 class="text-5xl">Academic Excellence</h4>
          <p class="text-xl">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Accusantium vitae, a cum mollitia fuga in eaque perferendis quidem tempore. Nostrum accusamus tempore et exercitationem fugit. Nostrum perspiciatis consequatur laborum ut!</p>
          <button class="border-[1px] border-white rounded-3xl w-32 px-4 py-2 hover:bg-white hover:text-blue-950 transition-[.1s]">Read More</button>
        </div>
      </div>
      <div class="flex flex-row justify-between gap-8 h-full items-center">
        <div class="flex flex-col gap-6 ml-8">
          <h4 class="text-5xl">A Happy Learning Environment</h4>
          <p class="text-xl">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Accusantium vitae, a cum mollitia fuga in eaque perferendis quidem tempore. Nostrum accusamus tempore et exercitationem fugit. Nostrum perspiciatis consequatur laborum ut!</p>
          <button class="border-[1px] border-white rounded-3xl w-32 px-4 py-2 hover:bg-white hover:text-blue-950 transition-[.1s]">Read More</button>
        </div>
        <div class="w-full h-full bg-[url('./images/dgu.jpg')] bg-center bg-cover"></div>
      </div>
    </div>
    <div class="flex flex-col gap-8 mx-[5vw] text-zinc-700">
      <h2 class="text-5xl">News</h2>
      <div class="flex flex-row gap-6">
        <div v-for="post in 4" :key="post" class="flex flex-col gap-4 h-fit max-h- w-full">
          <div class="bg-[url('./images/dgu.jpg')] bg-cover w-full aspect-[2/1.3] rounded-xl"></div>
          <p>August 21, 2024</p>
          <h6 class="text-3xl">The Junior Prep Collaborative Adventure</h6>
          <p class="text-xl">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Enim officia corrupti quia unde assumenda maxime ad voluptate accusamus, veritatis illum dicta molestias quam recusandae perferendis, ipsam autem, error iure magni!</p>
          <a href="/" class="text-xl underline cursor-pointer hover:opacity-[.8]">Read More</a>
        </div>
      </div>
    </div>
  </main>

  <footer class="bg-blue-950 pt-[5vw] pb-[.5vw] flex flex-col text-white">
    <div class="flex flex-row items-center mx-[5vw] justify-between">
      <div class="flex flex-row gap-4 items-center">
        <img src="./images/logo2.png" alt="" width="50">
        <p class="text-3xl">Дагестанский Государственный Университет</p>
      </div>
      <div class="flex flex-row gap-2">
        <a v-for="soc in 3" :key="soc" href="/" class="w-10 h-10 bg-white rounded-full cursor-pointer hover:bg-zinc-300"></a>
      </div>
    </div>
    <hr class="w-full left-0 my-8">
    <div class="mx-[5vw] flex flex-row justify-between items-center">
      <nav class="grid grid-cols-3 gap-y-1 gap-x-8 w-fit">
        <a href="/" class="hover:underline">Университет</a>
        <a href="/" class="hover:underline">Образование</a>
        <a href="/" class="hover:underline">Структура</a>
        <a href="/" class="hover:underline">Наука</a>
        <a href="/" class="hover:underline">Пресс-центр</a>
        <a href="/" class="hover:underline">Прием-2024</a>
        <a href="/" class="hover:underline">Абитуриенту</a>
        <a href="/" class="hover:underline">Студентам</a>
        <a href="/" class="hover:underline">Сотрудникам</a>
        <a href="/" class="hover:underline">Контакты</a>
        <a href="/" class="hover:underline">Галерея</a>
        <a href="/" class="hover:underline">Новости</a>
        <a href="/" class="hover:underline">Архив</a>
        <a href="/" class="hover:underline">Сведения</a>
      </nav>
    </div>
    <p class="flex flex-row gap-1 self-center text-zinc-300"><span>&copy</span>developed by magnus</p>
  </footer>
</template>