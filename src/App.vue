<template>
  <q-layout>
      <q-header class="bg-color bayangan text-dark" style="height:100px">
        <q-toolbar>
          <q-img src="img/logokafe.png" class="q-ml-xl" style="width:90px;"/>
          <q-space/>
          <div class="q-mt-md SourceSerifPro">
            <q-btn label ="shop" class="q-mr-lg" flat rounded color="white">
              
            </q-btn>

            <q-btn label ="menu" class="q-mr-lg" flat rounded color="white">
              
            </q-btn>

            <q-btn label ="about" class="q-mr-lg" flat rounded color="white">
              
            </q-btn>

            <q-btn label ="contact" class="q-mr-lg" flat rounded color="white">
              
            </q-btn>
          </div>
        </q-toolbar>
      </q-header>
      <q-page-container>
        <router-view/>
      </q-page-container>
  </q-layout>
</template>


<script>
export default {

}
</script>


<style>
@font-face {
  font-family: SourceSerifPro;
  src: url(C:/laragon/www/porjec1/src/assets/SourceSerifPro-Regular.otf);
}

.my-font {
  font-family: 'SourceSerifPro';
}
</style>