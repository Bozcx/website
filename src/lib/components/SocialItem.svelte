<script lang="ts">
  export let href: string;
  export let title: string;
  export let image: string;
  export let imageAltText: string;
  export let imageHeight: number;

  const DEFAULT_HEIGHT = 25;
</script>

<a class="socialItem"
  href = {href}
  title = {title}>
  <img src={image} alt={imageAltText} height="{imageHeight || DEFAULT_HEIGHT}">
</a>

<style>
  .socialItem{
  display:flex;
  align-items: center;
}
</style>
