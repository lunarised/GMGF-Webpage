<template>
<div>


<div class="b"> <b> Regular NavBar</b> </div>
<div class="b"> <b> Floating maybe? </b> </div>
<div class="b"> <b> Floating maybe? </b> </div>
<div class="b"> <b> Floating maybe? </b> </div>
<div class="b"> <b> Floating maybe? </b> </div>
<div id="end"> </div>
</div>
</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

div {
  background-color: #00cc00;
  margin-top: 0px;
}
#end{
  clear: both;
}




.b{ width: 20%;
    margin-left: auto;
    margin-right: auto;
    color: #dd0000;
    float: left;
    padding: 0;
    }
*.last{
  clear:left;
}


</style>
