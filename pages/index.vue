
<template>
  <Head>
    <Title>INICIO</Title>
    <Meta name="description" />
  </Head>
  <section class="banner h-[80vh] bg-black text-white flex justify-center items-center p-10 rounded-b-[3rem]">
    <h1 class="text-center font-bold text-3xl">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate, odio culpa quidem magni fugit nemo!</h1>
  </section>
  <section class="max-w-screen-2xl flex-col rounded-full bg-white p-4 flex justify-center items-center">
    <h2 class="text-3xl font-semibold text-red-700">En N-INNOVATIONS BIOSUPPLY te ofrecemos: </h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 max-w-screen-lg place-content-center place-items-center">
        <span>
          Equipo de laboratorio
        </span>
        <svg  xmlns="http://www.w3.org/2000/svg"  width="140"  height="140"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round"  class="icon icon-tabler icons-tabler-outline icon-tabler-microscope"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M5 21h14" /><path d="M6 18h2" /><path d="M7 18v3" /><path d="M9 11l3 3l6 -6l-3 -3z" /><path d="M10.5 12.5l-1.5 1.5" /><path d="M17 3l3 3" /><path d="M12 21a6 6 0 0 0 3.715 -10.712" /></svg>
        <span>
          Equipo de laboratorio
        </span>
        <svg  xmlns="http://www.w3.org/2000/svg"  width="140"  height="140"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round"  class="icon icon-tabler icons-tabler-outline icon-tabler-microscope"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M5 21h14" /><path d="M6 18h2" /><path d="M7 18v3" /><path d="M9 11l3 3l6 -6l-3 -3z" /><path d="M10.5 12.5l-1.5 1.5" /><path d="M17 3l3 3" /><path d="M12 21a6 6 0 0 0 3.715 -10.712" /></svg>
        <span>
          Equipo de laboratorio
        </span>
        <svg  xmlns="http://www.w3.org/2000/svg"  width="140"  height="140"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round"  class="icon icon-tabler icons-tabler-outline icon-tabler-microscope"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M5 21h14" /><path d="M6 18h2" /><path d="M7 18v3" /><path d="M9 11l3 3l6 -6l-3 -3z" /><path d="M10.5 12.5l-1.5 1.5" /><path d="M17 3l3 3" /><path d="M12 21a6 6 0 0 0 3.715 -10.712" /></svg>
    </div>
  </section>
</template>
<style>
  h1{
    animation: normal 2s entryTitle;
  }
  @keyframes entryTitle {
    0%{
      transform: scale(.4);
    }
    100%{
      transform: scale(1);
    }
  }
  .banner{
    animation: normal 2s entryBanner;
  }
  @keyframes entryBanner {
    0%{
      transform: translateY(-100%);
    }
    100%{
      transform: translateY(0);
    }
  }
</style>