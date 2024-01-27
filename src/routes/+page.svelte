<script>
    import { goto } from "$app/navigation";
    import { onMount } from "svelte";

    onMount(()=>goto('/users/auth/login'))
</script>