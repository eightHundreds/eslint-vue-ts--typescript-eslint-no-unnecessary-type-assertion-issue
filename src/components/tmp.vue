<script lang="ts">
/* eslint-disable class-methods-use-this */
export default class Cmp {
  get a() {
    const list: Array<string> = [];
    return list;
  }

  async mounted() {
    this.a as Array<string>;
  }
}
</script>
