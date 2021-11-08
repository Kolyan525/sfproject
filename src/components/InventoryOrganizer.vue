<template>
  <v-app>
    <v-container fluid>
      <v-row align-content="center" class="justify-center align-center d-flex" :class="{'flex-column-reverse': $vuetify.breakpoint.xs}">
        <v-col class="pa-sm-16 io-column" cols="12" sm="6" style="left: 250px">
          <h2 class="text-h3 font-weight-bold mb-7">Система Інвентаризації</h2>
          <p class="text-sm-h4 text-h5" style="line-height: 5vh"> <!-- 49px -->
            IO — це система інвентаризації розроблена для ведення
            електронного обліку обладнання
            та ліцензій програмного забезпечення на підприємстві.</p>
          <v-card-actions class="pa-0 justify-center justify-sm-start">
            <v-btn
                class="white--text rounded-lg"
                color="#7683F7"
                height="5vh"
                style="border-radius: 15px !important;"
                width="220px"
            >
              Увійти
            </v-btn>
          </v-card-actions>
        </v-col>
        <v-col class="io-column pr-10" cols="11" sm="5">
          <div class="io-img-container">
            <v-img contain src="../assets/IOB.svg" width="100vh"></v-img>
          </div>
        </v-col>
      </v-row>


    </v-container>
  </v-app>
</template>

<script>
export default {
  name: "InventoryOrganizer"
}

</script>
<style scoped>

.container {
  font-family: Nunito, serif !important;
  background-color: rgba(217, 220, 245, 0.5);
}

@media (max-width: 968px) {
  .io-column {
    flex: 0 0 100% !important;
    max-width: 100%;
  }
}

.io-img-container {
  padding-right: 100px;
}

.rounded-lg {
  border-radius: 15px !important;
}

/*.v-btn {*/
/*  width: 220px;*/
/*  height: 50px;*/
/*  cursor: pointer;*/
/*  background: #7683f7;*/
/*  border-radius: 15px;*/
/*  color: white;*/
/*  font-family: Nunito;*/
/*  font-style: normal;*/
/*  font-weight: bold;*/
/*  font-size: 18px;*/
/*}*/

</style>
