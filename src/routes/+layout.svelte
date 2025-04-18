export const prerender = true;
<script lang="ts">
    import '../app.css';
</script>

<nav style="justify-content: center;">
    <a href="/photos">Photos</a>
    <a href="/">Home</a>
    <a href="/letters">Letters</a>
</nav>

<slot />
