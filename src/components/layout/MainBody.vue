<template>
  <div>
    <h1>Body</h1>
    <home-page />
    <publicar-vaga />
  </div>
</template>

<script>
import HomePage from "@/components/views/HomePage.vue";
import PublicarVaga from "@/components/views/PublicarVaga.vue";

export default {
  name: "MainBody",
  components: {
    HomePage,
    PublicarVaga,
  },
  methods: {},
  beforeCreate() {
    console.log("Antes de criar");
  },
  created() {
    console.log("criado");
  },
  beforeMount(){
    console.log("Antes de montar");
  },
  mounted(){
    console.log("montado");
  },
  beforeUpdate(){
    console.log("Antes de montar");
  },
  Updated(){
    console.log("atualizado");
  },
  beforeUnmount(){
    console.log("Antes de desmontar");
  },
  unmounted(){
    console.log("desmontado");
  },
  errorCaptured(){
    console.log("erro capturado");
  },
  renderTracked(){
    console.log("Re-renderização capturado");
  },
  renderTriggered(){
    console.log("Re-renderização acionada");
  },
  activated(){
    console.log("Ativado!");
  },
  deactivated(){
    console.log("desativado!");
  }

};
</script>

<style module>
h1 {
  color: green;
}
.teste1 {
  background-color: red;
}
#teste2 {
  background-color: yellow;
}
</style>
