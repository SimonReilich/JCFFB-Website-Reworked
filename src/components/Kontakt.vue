<script></script>

<template>
  <div
    class="hero flex flex-start flex-col min-h-screen m-auto w-full md:w-3/5 min-w-128 max-w-4xl p-6 bg-base-200 shadow-xl">

    <h1 class="hero-content text-5xl font-bold bg-base-100 m-6 mt-24 h-60 w-full flex flex-row flex-start rounded-2.5xl"
      style="background-image: url('/src/assets/titel.jpg'); background-size: cover;">
      <img width="250" height="250" src="/src/assets/logo.png" class="fill-current m-2 drop-shadow-2xl"></img>
      <p class="flex-auto text-center m-2 text-slate-100 max-[960px]:text-3xl">Kontakt</p>
    </h1>
    <h2 class="hero-content text-2xl text-center m-2">Kontaktformular</h2>
    <div class="divider"></div>

    <input type="text" placeholder="Name" class="input input-bordered w-full max-w-144 m-2" />

    <input type="text" placeholder="E-Mail" class="input input-bordered w-full max-w-144 m-2" />

    <textarea class="textarea textarea-bordered w-full max-w-144 m-2" placeholder="Nachricht"></textarea>

    <button class="btn btn-primary m-2">Absenden</button>
  </div>
</template>

<style scoped></style>