<script lang="ts">
	import Footer from "./components/Footer.svelte";
	import Header from "./components/Header.svelte";
	import { DarkMode } from "./lib/DarkMode.store";
</script>

<main id={"main"} class={`${$DarkMode ? "dark" : ""} preload`}>
	<div class={"bg-[whitesmoke] transition-colors dark:bg-slate-800 dark:text-white min-h-screen flex flex-col"}>
		<Header />
		<div class={"sm:container mx-auto flex flex-col"}>
			<!-- BODY HERE -->
		</div>
		<Footer />
	</div>
</main>