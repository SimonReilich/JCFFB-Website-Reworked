<script setup>
// importieren aller Komponenten
import Start from './components/Start.vue';
import Judo from './components/Judo.vue';
import Trainings from './components/Trainings.vue';
import News from './components/News.vue';
import Personen from './components/Personen.vue';
import Kontakt from './components/Kontakt.vue';
import Termine from './components/Termine.vue';
import GJudo from './components/GJudo.vue';
import Satzung from './components/Satzung.vue';
import Impressum from './components/Impressum.vue';
import Datenschutz from './components/Datenschutz.vue';
import Formulare from './components/Formulare.vue';
</script>

<script>
export default {
  data() {
    return {
      // definieren aller Variablen
      page: 0,
    }
  },

  methods: {
    // definieren aller Methoden
    goStart() {
      this.page = 0
      console.log("Start " + this.page)
      window.scrollTo(0, 0);
    },

    goJudo() {
      this.page = 1
      console.log("Judo " + this.page)
      window.scrollTo(0, 0);
    },

    goTrainings() {
      this.page = 2
      console.log("Trainings " + this.page)
      window.scrollTo(0, 0);
    },

    goNews() {
      this.page = 3
      console.log("News " + this.page)
      window.scrollTo(0, 0);
    },

    goPersonen() {
      this.page = 4
      console.log("Personen " + this.page)
      window.scrollTo(0, 0);
    },

    goKontakt() {
      this.page = 5
      console.log("Kontakt " + this.page)
      window.scrollTo(0, 0);
    },

    goTermine() {
      this.page = 6
      console.log("Termine " + this.page)
      window.scrollTo(0, 0);
    },

    goGJudo() {
      this.page = 7
      console.log("G-Judo " + this.page)
      window.scrollTo(0, 0);
    },

    goSatzung() {
      this.page = 9
      console.log("Satzung " + this.page)
      window.scrollTo(0, 0);
    },

    goImpressum() {
      this.page = 10
      console.log("Impressum " + this.page)
      window.scrollTo(0, 0);
    },

    goDatenschutz() {
      this.page = 11
      console.log("Datenschutz " + this.page)
      window.scrollTo(0, 0);
    },

    goFormulare() {
      this.page = 12
      console.log("Formulare " + this.page)
      window.scrollTo(0, 0);
    },
  },

  components: {
    // deffinieren aller Komponenten
    Start,
    Judo,
    Trainings,
    News,
    Personen,
    Kontakt,
    Termine,
    GJudo,
    Satzung,
    Impressum,
    Datenschutz,
    Formulare,
  },
}
</script>

<template>
  <div class="bg-fixed bg-cover min-h-screen width-full" style="background-image: url('src//assets/background.jpg') ">

    <div class="navbar bg-base-100 fixed z-50 shadow-xl">
      <div class="flex-1">
        <a @click="goStart" lang="en" class="btn btn-ghost text-xl">Home</a>
      </div>
      <div class="flex-none">
        <ul class="menu menu-horizontal px-1">
          <li><a @click="goJudo">Judo</a></li>
          <li><a @click="goTrainings">Trainings</a></li>
          <li><a @click="goNews" lang="en">News</a></li>
          <li><a @click="goPersonen">Personen</a></li>
          <li><a @click="goKontakt">Kontakt</a></li>
          <label class="swap swap-rotate">
            
            <!-- this hidden checkbox controls the state -->
            <input type="checkbox" class="theme-controller" value="buisness" />
            
            <!-- sun icon -->
            <svg class="swap-off fill-current w-6 h-6 ml-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M5.64,17l-.71.71a1,1,0,0,0,0,1.41,1,1,0,0,0,1.41,0l.71-.71A1,1,0,0,0,5.64,17ZM5,12a1,1,0,0,0-1-1H3a1,1,0,0,0,0,2H4A1,1,0,0,0,5,12Zm7-7a1,1,0,0,0,1-1V3a1,1,0,0,0-2,0V4A1,1,0,0,0,12,5ZM5.64,7.05a1,1,0,0,0,.7.29,1,1,0,0,0,.71-.29,1,1,0,0,0,0-1.41l-.71-.71A1,1,0,0,0,4.93,6.34Zm12,.29a1,1,0,0,0,.7-.29l.71-.71a1,1,0,1,0-1.41-1.41L17,5.64a1,1,0,0,0,0,1.41A1,1,0,0,0,17.66,7.34ZM21,11H20a1,1,0,0,0,0,2h1a1,1,0,0,0,0-2Zm-9,8a1,1,0,0,0-1,1v1a1,1,0,0,0,2,0V20A1,1,0,0,0,12,19ZM18.36,17A1,1,0,0,0,17,18.36l.71.71a1,1,0,0,0,1.41,0,1,1,0,0,0,0-1.41ZM12,6.5A5.5,5.5,0,1,0,17.5,12,5.51,5.51,0,0,0,12,6.5Zm0,9A3.5,3.5,0,1,1,15.5,12,3.5,3.5,0,0,1,12,15.5Z"/></svg>
            
            <!-- moon icon -->
            <svg class="swap-on fill-current w-6 h-6 ml-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M21.64,13a1,1,0,0,0-1.05-.14,8.05,8.05,0,0,1-3.37.73A8.15,8.15,0,0,1,9.08,5.49a8.59,8.59,0,0,1,.25-2A1,1,0,0,0,8,2.36,10.14,10.14,0,1,0,22,14.05,1,1,0,0,0,21.64,13Zm-9.5,6.69A8.14,8.14,0,0,1,7.08,5.22v.27A10.15,10.15,0,0,0,17.22,15.63a9.79,9.79,0,0,0,2.1-.22A8.11,8.11,0,0,1,12.14,19.73Z"/></svg>
            
          </label>
        </ul>
      </div>
    </div>

    <Start v-if="page === 0" @goTrainings="goTrainings" />

    <Judo v-else-if="page === 1" />

    <Trainings v-else-if="page === 2" />

    <News v-else-if="page === 3" />

    <Personen v-else-if="page === 4" />

    <Kontakt v-else-if="page === 5" />

    <Termine v-else-if="page === 6" />

    <GJudo v-else-if="page === 7" />

    <Satzung v-else-if="page === 9" />

    <Impressum v-else-if="page === 10" />

    <Datenschutz v-else-if="page === 11" />

    <Formulare v-else-if="page === 12" />

    <footer class="footer p-10 bg-base-100 text-base-content shadow-xl">
      <aside>
        <img width="150" height="150" src="/src/assets/logo.png" class="fill-current" @click="goStart" alt="Logo des JC FFB"></img>
        <p>Judoclub Fürstenfeldbruck e.V.<br>gegründet 1978</p>
      </aside>
      <nav>
        <h6 class="footer-title">Menü</h6>
        <p class="link link-hover" @click="goTermine">Termine</p>
        <p class="link link-hover" @click="goGJudo">G-Judo</p>
        <a class="link link-hover" href="https://www.bayernjudo.de/">Bayerischer Judoverband</a>
        <a class="link link-hover" href="https://www.judobund.de/">Deutscher Judo-Bund</a>
      </nav>
      <nav>
        <h6 class="footer-title">Kontakt</h6>
        <p>Telefon: 0177 2704547</p>
        <p>Mail: lutz.meinhold@judoclub-ffb.de</p>
        <a class="link link-hover"
          href="https://www.facebook.com/Judoclub-F%C3%BCrstenfeldbruck-eV-213666331982425">Facebook: Judoclub
          Fürstenfeldbruck e.V. </a>
        <a class="link link-hover" href="https://www.instagram.com/judoclub_ffb/">Instagramm: @judoclub_ffb</a>
      </nav>
      <nav>
        <h6 class="footer-title">Rechtliches</h6>
        <p class="link link-hover" @click="goSatzung">Satzung</p>
        <p class="link link-hover" @click="goImpressum">Impressum</p>
        <p class="link link-hover" @click="goDatenschutz">Datenschutz</p>
        <p class="link link-hover" @click="goFormulare">Formulare</p>
      </nav>
    </footer>
  </div>
</template>

<style scoped></style>
