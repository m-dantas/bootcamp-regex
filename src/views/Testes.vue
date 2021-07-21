<template>
  <div class="testes">
    <HelloWorld :msg="msg" />
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld'
export default {
  name: 'Testes',
  components: {
    HelloWorld
  },
  data () {
    return {
      msg: 'Bem-vindo a página de Testes'
    }
  }
}
</script>

<style>

</style>
