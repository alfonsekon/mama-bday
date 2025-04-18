export const prerender = true;
<script lang="ts">
    import '../app.css';
    import { base } from '$app/paths';
</script>

<nav style="justify-content: center;">
    <a href="/photos">Photos</a>
    <a href="{base}/">Home</a>
    <a href="/letters">Letters</a>
</nav>

<slot />
