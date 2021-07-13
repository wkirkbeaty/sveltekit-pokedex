<script>
import Nav from "../components/nav.svelte";

</script>

<style global lang="postcss">
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
</style>

<div class="p-8 max-w-6xl mx-auto">
    <Nav/>
    <slot>
    </slot>
</div>




