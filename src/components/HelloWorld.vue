<template>
  <div>
     <button @click="forFn">点击</button>
  </div>
</template>
<script>
export default {
  props:{

  },
  components:{

  },
  data(){
    return {

    }
  },
  computed:{

  },
  methods:{
   forFn(){
     let data=[{
       name:"12"
     },
     {
       name:"12"
     },{
       name:"12"
     }]

     for(let i=0;i<data.length;i++){
      
         for(let key in data[i]){
           let c=data[i]
              console.log(data[i])
              console.log(key)
              console.log(c.name)
     }}
   }
  },
  created(){

  },
  mounted(){

  }
}
</script>
<style scoped lang="">

</style>