<script>
    import michelle from '../../static/picture-of-michelle.png';
    import FaGithub from 'svelte-icons/fa/FaGithub.svelte';
    import FaLinkedinIn from 'svelte-icons/fa/FaLinkedinIn.svelte';
    import FaSpotify from 'svelte-icons/fa/FaSpotify.svelte';
    import FaPaintBrush from 'svelte-icons/fa/FaPaintBrush.svelte';
    import FaInstagram from 'svelte-icons/fa/FaInstagram.svelte';

    import FaPython from 'svelte-icons/fa/FaPython.svelte';
    import FaReact from 'svelte-icons/fa/FaReact.svelte';
    import DiMongodb from 'svelte-icons/di/DiMongodb.svelte';
    import DiHtml5 from 'svelte-icons/di/DiHtml5.svelte';
    import DiPhotoshop from 'svelte-icons/di/DiPhotoshop.svelte';
    import DiIllustrator from 'svelte-icons/di/DiIllustrator.svelte';
    import DiCss3 from 'svelte-icons/di/DiCss3.svelte';
</script>
<body>
<main class="intro">
    <h1>Hi! My name is Michelle.</h1>
    <h2>I'm a Designer & Developer based in the San Francisco Bay Area.</h2>
<article class="bio">
    <img src={michelle} alt="picture of Michelle" class="profile_picture" />

    <p>I live a triple-life as a business owner running a photography &amp; design agency, traveling as a classical musician
    in an award-winning contemporary chamber ensemble that I founded, and as a growing developer pursuing a post-baccalaureate degree in computer science at
    Oregon State University.</p>

    <div class="skills">
        <div class="icon">

        </div>
    </div>
<div class="socials">
<div class="icon">
    <a href="https://github.com/michellemyers94" target="_blank"><FaGithub /></a>
    </div>

    <div class="icon">
        <a href="https://linkedin.com/in/michellemyers94" target="_blank"><FaLinkedinIn /></a>
        </div>

    <div class="icon">
        <a href="https://open.spotify.com/artist/0YpQpRCtGWFmgmuMfJsdxb?si=xOMIbvN6SYaB435qEenqCg" target="_blank"><FaSpotify /></a>
    </div>

    <div class="icon">
        <a href="https://mychelledesign.com" target="_blank"><FaPaintBrush /></a>
    </div>

    <div class="icon">
        <a href="https://instagram.com/musicalmichelle94" target="_blank"><FaInstagram /></a>
    </div>
</div>

<!--<p>Skills</p>-->
<!--    <div class="skills">-->

<!--        <div class="icon">-->
<!--        <FaPython />-->
<!--        </div>-->

<!--        <div class="icon">-->
<!--            <FaReact />-->
<!--        </div>-->

<!--        <div class="icon">-->
<!--            <DiHtml5 />-->
<!--        </div>-->

<!--        <div class="icon">-->
<!--            <DiCss3 />-->
<!--        </div>-->

<!--        <div class="icon">-->
<!--            <DiMongodb />-->
<!--        </div>-->

<!--        <div class="icon">-->
<!--            <DiPhotoshop />-->
<!--        </div>-->

<!--        <div class="icon">-->
<!--            <DiIllustrator />-->
<!--        </div>-->

<!--    </div>-->

</article>
</main>

</body>