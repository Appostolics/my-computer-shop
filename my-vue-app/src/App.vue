<template>
  <div>
      <HeaderComponent title="Вітаю у Vue-додатку" />
      <MessageComponent title="Привіт, Vue!" message="Я вмію створювати компоненти із пропсами!" />
  </div>
</template>
<script>
import HeaderComponent from './components/Header.vue';
import MessageComponent from './components/MessageComponent.vue';

export default{
  components:{
    HeaderComponent,
    MessageComponent
  }
}
</script>
