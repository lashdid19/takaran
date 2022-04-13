<script>
    export let value
</script>

<select class="rounded-md cursor-pointer flex font-semibold bg-pink-700 text-sm text-white w-full py-3 px-2 transition duration-300 justify-between appearance-none md:text-base hover:bg-pink-800" bind:value={value} on:change>
    <option selected disabled hidden>
        Pilih Ukuran :
    </option>
    <slot/>
</select>