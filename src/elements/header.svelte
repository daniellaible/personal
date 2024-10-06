<script lang="ts">

    import {goto} from "$app/navigation";

    export let location = '';


    function toDeveloper(){
        goto('/developer');
    }

    function toManager(){
        goto('/projectmanager');
    }

    function toAbout(){
        goto('/about');
    }

    function toContact(){
        goto('/contact');
    }

</script>

<div class="bg-gray-500" >

    <div class="grid grid-flow-row grid-cols-5 grid-rows-1 ">
        <div class="w-[300px] ml-6 mt-6 ">
            <img src="Dan.jpg" alt="Daniel Laible">
        </div>

        <div class="ml-12 col-span-4">

            <div class="grid grid-flow-row grid-cols-4 grid-rows-2">
                <div class="w-full mt-24 col-span-4">
                    Wer einen schlechten Prozess digitalisiert, bekommt einen schlechten, digitalen Prozess
                </div>

                <div class="flex flex-col">
                    {#if location === 'developer'}
                        <div class="mt-28 text-green-700 bg-yellow-600 content-baseline">
                            <button type="button" on:click={toDeveloper} >Entwicker</button>
                        </div>
                    {:else}
                        <div class="mt-28 text-blue-700 bg-yellow-600 content-baseline">
                            <button type="button" on:click={toDeveloper} >Entwicker</button>
                        </div>
                    {/if}

                </div>

                <div class="flex flex-col">
                    {#if location === 'manager'}
                        <div class="mt-28 text-green-700 bg-yellow-600 content-baseline">
                            <button type="button" on:click={toManager} >Agiler Manager</button>

                        </div>
                    {:else}
                        <div class="mt-28 text-blue-700 bg-yellow-600 content-baseline">
                            <button type="button" on:click={toManager} >Agiler Manager</button>

                        </div>
                    {/if}


                </div>

                <div class="flex flex-col">
                    {#if location === 'about'}
                    <div class=" mt-28 text-green-700 bg-yellow-600 content-baseline">
                        <button type="button" on:click={toAbout} >Über mich</button>
                    </div>
                    {:else}
                        <div class=" mt-28 text-blue-700 bg-yellow-600 content-baseline">
                            <button type="button" on:click={toAbout} >Über mich</button>
                        </div>
                    {/if}
                </div>

                <div class="flex flex-col">
                    {#if location === 'contact'}
                    <div class=" mt-28 text-green-700 bg-yellow-600 content-baseline">
                        <button type="button" on:click={toContact} >Kontakt</button>
                    </div>
                    {:else}
                        <div class=" mt-28 text-blue-700 bg-yellow-600 content-baseline">
                            <button type="button" on:click={toContact} >Kontakt</button>
                        </div>
                    {/if}
                </div>

            </div>

        </div>

    </div>


</div>
