<template>
  <div>
    <PrimeiroComponente />
    <LifeCycle />
    <Form />
    <Info/>
    <Pessoa />
  </div>
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'
import Form from './components/Form.vue';
import Info from './components/Info.vue';
import Pessoa from './components/Pessoa.vue';

export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle,
    Form,
    Info,
    Pessoa
}
}
</script>
