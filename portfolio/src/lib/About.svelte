<script lang="ts">
    let currentYear  = new Date().getFullYear();
    let age = currentYear - 2004;
</script>
<div class="d-flex justify-content-start flex-column border border-black border-3 bg-light p-3">
    <h2>About.</h2>
    <div></div>
    <div>{age} years old.</div>
    <div></div>
</div>