<script>
    import Input from "./Input.svelte"
    
    export let showOption = false
    export let options = []
</script>

<div class="w-full h-full absolute top-0 left-0 w-full bg-pink-500 {showOption ? "block" : "hidden"}">
    <div class="bg-pink-500 w-full">
      <Input placeholder="Cari"/>
    </div>
    <div class="h-full bg-pink-500 w-full grid p-2 gap-1 grid-cols-3 overflow-y-scroll">
        {#each options as option}
            <button class="rounded-md text-left text-white py-1 px-2 hover:bg-pink-700">
                {option.name}
            </button>
        {/each}
    </div>
  </div>