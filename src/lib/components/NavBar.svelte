<script>
  import SocialItem from "$lib/components/SocialItem.svelte";
</script>

<div class="nav-container">
	<div class="nav-title-container">
		<span class="nav-title">Boz.cx</span>
	</div>

  <div class="navLinks">
    <div class="socials">
      <SocialItem title="GitHub" image="/img/github.svg" imageAltText="GitHub Logo"  href="https://github.com/bozcx"/>
    </div>
  </div>
</div>

<style>
	.nav-container{
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 20px;
      box-sizing: border-box;

      width: 100%;
      height: 80px;

      color: white;
	}

	.nav-title-container{
      display: flex;
      align-items: center;
      gap: 10px;
	}

	.nav-title{
      font-size: 1.5rem;
	}
  
  .navLinks {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px 30px;
  flex-wrap:wrap;
  }

  .socials{
        display: flex;
        align-items: center;
        gap: 30px;
}
</style>
