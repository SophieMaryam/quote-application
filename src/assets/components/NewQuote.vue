<template>
import { PassThrough } from 'stream';
    <div class="row">
      <form>
        <div class="col-sm-8 cold-sm-offset-2 col-xs-12 col-md-6 cold-md-offset-3">
          <label> Quote </label>
          <textarea class=form-control rows="3" v-model="quote"></textarea>
        </div>
      </form>
    </div>
</template>
<script>
  export default {
    data: function() {
      return {
        quote: ''
      };
    }
  }
</script>
<style>

</style>


