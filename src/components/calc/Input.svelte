<script>
    export let placeholder;
    export let value;
</script>

<input type="number" class="font-semibold outline-transparent shadow-md w-full p-3 placeholder-pink-300 transition text-pink-600 duration-300 focus:(shadow-transparent placeholder-transparent)" placeholder={placeholder} bind:value={value} on:input/>