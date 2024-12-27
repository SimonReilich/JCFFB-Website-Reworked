<script></script>

<template>
  <div
    class="hero flex flex-start flex-col min-h-screen m-auto w-full md:w-3/5 min-w-128 max-w-4xl p-6 bg-base-200 shadow-xl">

    <h1
      class="hero-content text-5xl font-bold bg-base-100 m-6 mt-24 h-60 w-full flex flex-row flex-start rounded-2.5xl" style="background-image: url('/src/assets/titel.jpg'); background-size: cover;">
      <img width="250" height="250" src="/src/assets/logo.png" class="fill-current m-2 drop-shadow-2xl fit"></img>
      <p class="flex-auto text-center m-2 text-slate-100 max-[960px]:text-3xl" lang="japanese">Hajime!</p>
    </h1>
    <h2 class="hero-content text-2xl text-center m-2">Herzlich Wilkommen beim Judoclub Fürstenfeldbruck!</h2>

    <div class="divider"></div>

    <div class="card w-96 bg-base-100 shadow-xl m-6">
      <figure><img src="/src/assets/anfängerUndWiedereinsteiger.jpeg" class="w-full cover" alt="Judotraining"/></figure>
      <div class="card-body">
        <h2 class="card-title">Anfänger und Wiedereinsteiger</h2>
        <p>sind in allen Trainings willkommen!</p>
        <div class="card-actions justify-center mt-3">
          <button class="btn btn-primary" @click="$emit('goTrainings')">Trainingszeiten</button>
        </div>
      </div>
    </div>

    <div class="divider"></div>

    <div class="w-full flex flex-col 3xl:flex-row flex-start justify-stretch align-top">
      <div class="flex-1 flex-col place-self-start">
        <h2 class="text-2xl text-center">Zertifizierter Verein <br> vom DJB</h2>
        <img width="400" src="/src/assets/zertifiziert.png" class="m-auto my-4" alt="Siegel des DJB"></img>
        <p class="m-4">Die erforderlichen Qualitätskriterien sind: qualifizierte Judotrainer, Dan-Träger im Verein,
          Kyu-Prüfungen nach DJB Richtlinien, regelmäßige Breitensportaktionen sowie die Teilnahme am Wettkampfbetrieb
          im Judo.</p>
      </div>

      <div class="flex-1 flex-col place-self-start">
        <h2 class="text-2xl text-center">Qualitätssiegel <br> "Top-Verein"</h2>
        <img width="250" src="/src/assets/qualität1.png" class="m-auto my-4" alt="Qualitätssiegel 'Topverein' des BJV"></img>
        <img width="250" src="/src/assets/qualität2.png" class="m-auto my-4" alt="Qualitätssiegel 'Junges Engagement' des BJV"></img>
        <img width="250" src="/src/assets/qualität3.png" class="m-auto my-4" alt="Qualitätssiegel 'Partnerverein Schulkooperation' des BJV"></img>
        <p class="m-4">Wir freuen uns vom Bayerischen Judo Verband mit dem Qualitätssiegel "Top-Verein" mit allen drei
          Sternen ausgezeichnet worden zu sein. Kriterien siehe www.bayernjudo.de/forum</p>
      </div>
    </div>
  </div>
</template>

<style scoped></style>