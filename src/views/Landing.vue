<template>
  <div>
    <navbar-component></navbar-component>
    <main>
      <header-component></header-component>
      <cards-holder-component></cards-holder-component>
      <info-component></info-component>
      <team-compnent></team-compnent>
      <contact-compnent></contact-compnent>
    </main>
    <footer-component></footer-component>
  </div>
</template>
<script>
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
import HeaderComponent from "../components/Header.vue";
import CardsHolderComponent from "../components/CardsHolder.vue";
import InfoComponent from "../components/Info.vue";
import TeamCompnent from "../components/Team.vue";
import ContactCompnent from "../components/Contact.vue";
export default {
  name: "landing-page",
  components: {
    NavbarComponent,
    FooterComponent,
    HeaderComponent,
    CardsHolderComponent,
    InfoComponent,
    TeamCompnent,
    ContactCompnent,
  }
}
</script>
