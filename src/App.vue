<template>
  <div id="app">
    App 컴포넌트
    <DatePicker></DatePicker>
  </div>
</template>

<script>
import DatePicker from './DatePicker.vue'

export default {
  // created(){
  //   console.log($.fn.jquery);
  //   console.log($.ui.version);
  // }
  // mounted(){
  //   $('#calendar').datepicker();
  // }
  components:{
    DatePicker
  }
}
</script>
