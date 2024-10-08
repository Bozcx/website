<script>
	let age = 20;

	const nowDate = Date.now();
	const birthDate = new Date(2004, 3, 3);

	const elapsedTime = nowDate - birthDate.getTime();
	const elapsedYears = Math.floor(elapsedTime / (1000 * 60 * 60 * 24 * 365));

	age = elapsedYears;
</script>


<section class="about-container">
	<div class="title">
		<span>About Me!</span>
	</div>
	<div class="about-second-container">
		<div class="center">
			<img class="image" src="/img/profile.jpg" alt="Profile Image"/>
		</div>
		<div class="desc">
			        <span>
            Hello! My name is Boz, and I'm a {age} year old developer from Canada. I love reading, and understanding how Games are made and their underlying mechanics. Currently I'm pursuing a Computer Programming and Analysis degree.
        </span>
		</div>
	</div>
</section>

<style>
    .about-container{
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 50px;
        width: 100%;
        padding: 30px 0;

        background-color: var(--primary-colour);

        color: white;
    }

    .title{
        display: flex;
        justify-content: center;
        gap: 15px;
        flex-wrap: wrap;
        margin: 0 30px;

        font-size: 3.25rem;
    }

    .about-second-container {
        display: flex;
        gap: 30px;
        width: min(85%, 1100px);
    }

    .image {
        width: min(300px, 80vw);

        border-radius: 20px;
    }

    .desc {
        display: flex;
        flex-direction: column;
        text-align: left;
        gap: 20px;

        font-size: 1.5rem;
    }

</style>