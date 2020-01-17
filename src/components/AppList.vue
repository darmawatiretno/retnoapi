<template>
  <div>
    <h4 style="margin: 0; padding: 3% 0% 0% 3%">My Api</h4>
    <div style="margin: 3%">
      <q-card inline style="min-width: 300px; width: 30%; height: 210px;">
        <q-card-media style="float: left; padding: 10px">
          <img src="~assets/Quasar.png">
        </q-card-media>
        <q-card-title style="padding: 0px; padding-top: 10px;"></q-card-title>
        <q-card-main>
          <q-checkbox readonly v-model="check1" style="float: right"/>
          <p class="text-faded">Framework JavaSript yang bisa digunakan untuk mengembangkan aplikasi single-page.</p>
        </q-card-main>
        <q-card-separator/>
        <q-card-main>
          Browser yang mendukung mencakup semua browser seperti : Google Chrome, Firefox, Edge, Safari dan Opera. Untuk tampilan asli pada perangkat seluler , pengembang bisa menyesuaikan gaya untuk setiap Platform. .
        </q-card-main>
      </q-card>
      <q-card inline style="min-width: 300px; width: 30%; height: 210px; margin: 0% 1%">
        <q-card-media style="float: left; padding: 10px">
          <img src="~assets/unity.png">
        </q-card-media>
        <q-card-title style="padding: 0px; padding-top: 10px;"></q-card-title>
        <q-card-main>
          <q-checkbox readonly v-model="check1" style="float: right"/>
          <p class="text-faded">Unity adalah mesin permainan cross-platform yang dikembangkan oleh Unity Technologies, </p>
        </q-card-main>
        <q-card-separator/>
        <q-card-main>Unity merupakan game engine yang ber-multiplatform. Unity mampu di publish menjadi Standalone  (.exe), berbasis web, berbasis web, Android, IoS Iphone, XBOX, dan PS3. Walau bisa dipublish ke berbagai platform, Unity perlu lisensi untuk dapat dipublish ke platform tertentu. Tetapi Unity menyediakan untuk free user dan bisa di publish dalam bentuk Standalone (.exe) dan web. Untuk saat ini Unity sedang di kembangkan berbasis AR (Augment Reality)..</q-card-main>
      </q-card>
            <q-card inline style="min-width: 300px; width: 30%; height: 210px;">
        <q-card-media style="float: left; padding: 10px">
          <img src="~assets/android.png">
        </q-card-media>
        <q-card-title style="padding: 0px; padding-top: 10px;"></q-card-title>
        <q-card-main>
          <q-checkbox readonly v-model="check1" style="float: right"/>
          <p class="text-faded">Android Studio merupakan Integrated Development Environment (IDE) resmi υntυk pengembangan aplikasi Android.. </p>
        </q-card-main>
        <q-card-separator/>
        <q-card-main>
          Platform android terdiri ԁагі Sistem Operasi berbasis Linux, sebuah GUI (Graphic User Interface), sebuah web browser ԁаn Aplikasi Studio End-User уаng dapat ԁі download ԁаn јυgа para pengembang Ьіѕа ԁеngаn leluasa berkarya serta menciptakan aplikasi уаng tегЬаіk ԁаn terbuka υntυk digunakan оӏеһ ЬегЬаgаі macam perangkat.
        </q-card-main>
      </q-card>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AppList',
  data () {
    return {
      check1: false
    }
  }
}
</script>

<style>
</style>
