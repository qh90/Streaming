<script type="ts">
    import HomeLayout from "$lib/layouts/HomeLayout.svelte";
    import Banner from "$lib/components/pages/home/Banner.svelte";
    import SupportGroups from "$lib/components/pages/home/SupportGroups.svelte";
    import Features from "$lib/components/pages/home/Features.svelte";
    import HighPoints from "$lib/components/pages/home/HighPoints.svelte";
    import Status from "$lib/components/pages/home/Status.svelte";
    import Blog from "$lib/components/pages/home/Blog.svelte";
    import Support from "$lib/components/pages/home/Support.svelte";
    import ConnectDiscord from "$lib/components/pages/home/ConnectDiscord.svelte";
    import Footer from "$lib/layouts/Footer.svelte";
</script>

<HomeLayout>
    <Banner />
    <SupportGroups />
    <Features />
    <HighPoints />
    <Status />
    <Blog />
    <Support />
    <ConnectDiscord />
    <Footer />
</HomeLayout>