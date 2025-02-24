<script>
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<Header />

<main>
    <section class="hero">
        <div class="hero-content">
            <h1>Featured Works</h1>
            <p>
                We work with a lots of great people to give them wide range of
                experiences. Here’s our works
            </p>
        </div>
    </section>

    <section class="projects">
        <div class="project-card project-large">
            <div class="project-image">
                <img src="/image1.png" alt="Project Image 1" />
            </div>
            <h3>Friends Entertainment</h3>
            <p>
                A partner for clients in any industry that fulfils their
                particular needs
            </p>
        </div>

        <div class="project-card">
            <div class="project-image">
                <img src="/image2.png" alt="Project Image 2" />
            </div>
            <h3>Friends Entertainment</h3>
            <p>
                A partner for clients in any industry that fulfils their
                particular needs
            </p>
        </div>

        <div class="project-card move-right">
            <div class="project-image bg">
                <img src="/image3.png" alt="Project Image 3" />
            </div>
            <h3>Friends Entertainment</h3>
            <p>
                A partner for clients in any industry that fulfils their
                particular needs
            </p>
        </div>

        <div class="project-card project-large">
            <div class="project-image">
                <img src="/image1.png" alt="Project Image 4" />
            </div>
            <h3>Friends Entertainment</h3>
            <p>
                A partner for clients in any industry that fulfils their
                particular needs
            </p>
        </div>

        <div class="project-card">
            <div class="project-image">
                <img src="/image2.png" alt="Project Image 5" />
            </div>
            <h3>Friends Entertainment</h3>
            <p>
                A partner for clients in any industry that fulfils their
                particular needs
            </p>
        </div>

        <div class="project-card move-right">
            <div class="project-image bg">
                <img src="/image3.png" alt="Project Image 6" />
            </div>
            <h3>Friends Entertainment</h3>
            <p>
                A partner for clients in any industry that fulfils their
                particular needs
            </p>
        </div>
    </section>
</main>

<Footer />
