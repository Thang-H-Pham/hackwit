<script lang="ts">
    import { Button } from "m3-svelte";
</script>

<svelte:head>
	<title>HackWIT - Contact</title>
</svelte:head>

<!-- Header -->
<div class="flex flex-row justify-center items-center mt-12 md:mt-24 px-4 text-center sm:text-left">
    <b><h1 class="roboto-flex-wit-main text-4xl sm:text-6xl md:text-7xl leading-tight s-PalH6l0zoH1z " style="color:rgba(41, 106, 72, 1)">Contact</h1></b>
</div>

<!-- Divider -->
<div class="flex justify-center items-center mt-6 px-4 sm:px-6">
    <hr class="w-full max-w-5xl border-t-[1px] border-gray-300 dark:border-gray-1000 my-6" />
</div>

<!-- Navigation Buttons -->
<div class="flex flex-wrap justify-center items-center mt-4 peak gap-3 sm:gap-4 px-4">    
    <Button style="font-size: 1.3rem; font-weight: 500;">
        About
    </Button>
</div>


















<div class="flex justify-center items-center mt-8 px-4 sm:px-6 flex-col gap-4">
    <h2> hackathon@hackwit.org </h2>
    <div class="flex flex-row gap-4">
        <Button square variant="tonal" onclick={() => window.open('https://github.com/WITCodingClub/calendar', '_blank')}>
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path fill="currentColor" d="M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h7v2H5v14h14v-7h2v7q0 .825-.587 1.413T19 21zm4.7-5.3l-1.4-1.4L17.6 5H14V3h7v7h-2V6.4z"/></svg>        
            Github
        </Button>
        <Button square variant="tonal" onclick={() => window.open('https://discord.gg/fkeM94snmy', '_blank')}>
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path fill="currentColor" d="M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h7v2H5v14h14v-7h2v7q0 .825-.587 1.413T19 21zm4.7-5.3l-1.4-1.4L17.6 5H14V3h7v7h-2V6.4z"/></svg>        
            Discord
        </Button>
        <Button square variant="tonal" onclick={() => window.open('https://www.instagram.com/wit_coding_club/', '_blank')}>
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path fill="currentColor" d="M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h7v2H5v14h14v-7h2v7q0 .825-.587 1.413T19 21zm4.7-5.3l-1.4-1.4L17.6 5H14V3h7v7h-2V6.4z"/></svg>        
            Instagram
        </Button>
    </div>
</div>