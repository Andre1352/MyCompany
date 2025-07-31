<template>
  <div>
    <HeaderComponent title="hallo!" />
    <MessageComponent 
      title="Привіт, Vue!" 
      message="Я вмію створювати компоненти із пропсами!" 
    />
    <MessageComponent 
      title="Що далі?" 
      message="Тепер я можу передавати різні дані в компоненти!" 
    />
    <MessageComponent 
      title="Що тепер?" 
      message="Тепер я можу передавати різні дані в компоненти і вмкористовувати їх!" 
    />
  </div>
</template>
<script>
import HeaderComponent from "./components/Header.vue";
import MessageComponent from "./components/MessageComponent.vue";
export default {
  components: {
    HeaderComponent,
    MessageComponent
  }
};
</script>