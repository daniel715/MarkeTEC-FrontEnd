<template>
  <div class="home">
    <PaginaPrincipal/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import PaginaPrincipal from '@/components/PaginaPrincipal/PaginaPrincipal.vue'; // @ is an alias to /src

@Component({
  components: {
    PaginaPrincipal
  },
})
export default class Home extends Vue {}
</script>
