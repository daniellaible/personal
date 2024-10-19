<script lang="ts">

    import {goto} from "$app/navigation";
    import {onMount} from "svelte";

    export let location = '';

    let quote: string[] = [
        "Wer einen schlechten analogen Prozess digitalisiert, erhält einen schlechten, digitalen Prozess",
        "The latest shit is oftmals der neueste Scheiss",
        "Wurde dieselbe Sau nicht schon vor ein paar Jahren durchs Dorf getrieben?",
        "Es gibt keine gute Programmiersprache - daher gibt es soviele davon",
        "Guter Code liest sich wie ein Buch - schlechter Code gar nicht",
        "Der produktivste Tag, war der, an dem ich 1000 Zeilen gelöscht habe",
        "Code lügt nicht, Kommentare schon",
        "It works on your machine - unfortunately you never ship your machine",
        "Zuerst löst man das Problem, dann schreibt man den Code",
        "Die Abwesenheit eines Fehlers ist nicht beweisbar",
        "Der Unterschied zwischen Theorie und Praxis ist in der Praxis größer als in der Theorie",
        "Everything should be made as simple as possible, but not simpler",
        "Wer Code aus StackOverflow kopiert sollte diesen nicht aus der Frage heraus kopieren"
    ]
    let randomNumber: number;

    onMount(()=>{
        randomNumber =  Math.floor(Math.random() * quote.length);
    })


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

<div class="bg-gray-100" >

    <div class="grid grid-flow-row grid-cols-5 grid-rows-1 ">
        <div class=" ml-20 mt-6 ">
            <img class="rounded-full w-60 h-56" src="Dan.jpg" alt="Daniel Laible">
        </div>

        <div class="ml-12 col-span-4">

            <div class="grid grid-flow-row grid-cols-4 grid-rows-2">
                <div class="w-full mt-36 col-span-4">
                    {quote[randomNumber]}
                </div>

                <div class="flex flex-col">
                    {#if location === 'developer'}
                        <div class="mt-28 text-2xl text-sky-800 content-baseline">
                            <button type="button" on:click={toDeveloper} >Entwicker</button>
                        </div>
                    {:else}
                        <div class="mt-28 text-xl text-gray-900 content-baseline">
                            <button type="button" on:click={toDeveloper} >Entwicker</button>
                        </div>
                    {/if}

                </div>

                <div class="flex flex-col">
                    {#if location === 'manager'}
                        <div class="mt-28 text-2xl text-sky-800 content-baseline">
                            <button type="button" on:click={toManager} >Agiler Manager</button>

                        </div>
                    {:else}
                        <div class="mt-28 text-xl text-gray-900 content-baseline">
                            <button type="button" on:click={toManager} >Agiler Manager</button>

                        </div>
                    {/if}


                </div>

                <div class="flex flex-col">
                    {#if location === 'about'}
                    <div class="mt-28 text-2xl text-sky-800 content-baseline">
                        <button type="button" on:click={toAbout} >Über mich</button>
                    </div>
                    {:else}
                        <div class=" mt-28 text-xl text-gray-900 content-baseline">
                            <button type="button" on:click={toAbout} >Über mich</button>
                        </div>
                    {/if}
                </div>

                <div class="flex flex-col">
                    {#if location === 'contact'}
                    <div class=" mt-28 text-2xl text-sky-800 content-baseline">
                        <button type="button" on:click={toContact} >Kontakt</button>
                    </div>
                    {:else}
                        <div class=" mt-28 text-xl text-gray-900 content-baseline">
                            <button type="button" on:click={toContact} >Kontakt</button>
                        </div>
                    {/if}
                </div>

            </div>

        </div>

    </div>


</div>
