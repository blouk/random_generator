<template>
<div class="container">
  <div class="row">
    <div class="interface container mw-100">
      <h1 class="mt-3">Random generator</h1>
      <form action="#">
        <div class="src mt-3 mb-3">
          <label for="src">Source</label>
           <textarea type="text" class="form-control" id="src" aria-describedby="soruce" placeholder="é me entreu ton taixteu"/>

           <button class="btn btn-primary float-right mt-2" name="translate">Randomis-ed</button>
         </div>
         <div class="clearfix"/>
  <div class="output mt-3 mb-4">
    <label for="src">Source</label>
     <textarea type="text" readonly class="form-control" id="src" aria-describedby="soruce" placeholder="é me entreu ton taixteu"/>
  </div>
</form>
</div>
</div></div>
</template>

<script>
export default {
  name: 'RandomGenerator',
  data () {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.interface {
  border-radius: 15px;

  background-color: white;
}
</style>
