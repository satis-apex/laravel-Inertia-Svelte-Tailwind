<script>
    import { inertia, Link } from "@inertiajs/inertia-svelte";

    export let user;
</script>

<a href="/" use:inertia>Home</a>
<a href="/about" use:inertia>About</a>
<h1 class="text-3xl font-bold underline">
    hello {user}, from svelte about
</h1>
