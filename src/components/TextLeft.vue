<template>
  <v-container>
    <v-row
      text-left
      wrap
    >
      <v-col cols="10" lg="8" class="mx-auto">
        <div :class="{'display-1': $vuetify.breakpoint. mdAndDown, 'display-3': $vuetify.breakpoint. mdAndUp}">
          Neighborrow
        </div>
        <div class="text--primary font-italic font-weight-light	mt-6">
          <p>
            Wiertarka, sokowirówka, transporter dla kota, namiot gospodarczy, powiększalnik, odkurzacz próżniowy.
          </p>
          <p>
            Tworzymy sąsiedzką wypożyczalnię wszelkich sprzętów w Warszawie. Posiadasz zestaw do warzenia piwa, który wykorzystujesz raz do roku? Potrzebujesz pożyczyć kuchenkę turystyczną na wyjazd w Bieszczady? Neighborrow powstaje aby połączyć posiadających z potrzebującymi mieszkającymi w jednym mieście, po sąsiedzku.
          </p>
          <p>
            Masz pytania, chciałabyś/chciałbyś się z nami podzielić swoimi przemyśleniami? Prosimy o kontakt na <a href="mailto:czesc@neighborrow.pl">czesc@neighborrow.pl</a>.
          </p>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'TextLeft',

  data: () => ({
  }),
};
</script>
