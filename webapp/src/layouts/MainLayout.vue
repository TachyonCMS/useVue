<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>

        <q-toolbar-title>
          useVue.org - Tools to speed Vue adoption
        </q-toolbar-title>

        <div class="text-caption">Est. Aug 2022</div>
      </q-toolbar>
    </q-header>



    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from 'vue'


export default defineComponent({
  name: 'MainLayout',

  components: {
  },

  setup () {


    return {

    }
  }
})
</script>
