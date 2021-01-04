<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Logo UNDB"
          class="shrink mr-2"
          contain
          src="https://www.undb.edu.br/hs-fs/hubfs/logobranco.png?width=1209&name=logobranco.png"
          transition="scale-transition"
          width="80"
        />

        <spam class="red--text">
          <!--aqui pode ir texto do lado da logo undb-->
        </spam>
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="#"
        target="_blank"
        text
      >
        <span class="mr-2">Agendamento</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
