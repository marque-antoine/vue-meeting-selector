<template>
  <div id="whatsnew" class="what-s-new">
    <h3>
      <a href="#whatsnew">#</a>
      What's new
    </h3>
    <ul>
      <li>
        <h6>1.1.0</h6>
        <p>Set possible to have multi meetings selected</p>
      </li>
      <li>
        <h6>1.0.0</h6>
        <p>First release !!</p>
      </li>
    </ul>
  </div>
</template>

<script lang="ts">
import {
  Component,
  Vue,
} from 'vue-property-decorator';

@Component({
  name: 'Introduction',
})
export default class Introduction extends Vue {

}
</script>

<style scoped lang="scss">
.what-s-new {
  margin-top: 3em;
  padding-top: 3em;
}
</style>
