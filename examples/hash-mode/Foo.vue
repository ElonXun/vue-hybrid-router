<template lang="html">
    <div>
        this is Foo value is {{value}} 
        <p @click="changeValue">changevalue + 1</p>

    </div>
</template>

<script>

export default {
  data(){
    return{
        value: 1,
    }
  },
  methods:{
      changeValue: function(){
          this.value = this.value + 1;
      }
  },
  mounted:function(){
  }
}
</script>

<style lang="css">
</style>
