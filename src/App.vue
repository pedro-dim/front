  <template>
    
  <div >
  
    <Main/>
   
  
  </div>
  </template>




<script>

import HelloWorld from './components/HelloWorld.vue'
import Main from './components/Main.vue'

export default{

components:{Main},
data(){

return{



}

}


}

</script>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
