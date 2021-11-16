<script>
    import {
        Button
    } from "smelte";

    // import image from "svelte-image";
    
    // svelte({
    //     preprocess: image(),
    // })
    
    import {
        Image
    } from "smelte";
    // const range = [...new Array(50)];
</script>


<div class="py-4">
    <Button light class ='text-accent-900 font-bold transition duration-500 ease-in-out hover:bg-primary-600 hover:text-white-main transform hover:-translate-y-1 hover:scale-110 ...'>Adote Aqui</Button>
</div>

<!-- {#each range as _, i} -->

    <div class="p-5 grid grid-cols-3 gap-6 flex items-center justify-center">
        <img src="/imagens/cachorro1.jpg"  alt="cachorro1"/>
        <img src="/imagens/cachorro2.jpg" alt="cachorro2"/>
        <img src="/imagens/cachorro3.jpg" alt="cachorro3" />
        <img src="/imagens/cachorro4.jpg" alt="cachorro4" />
        <img src="/imagens/cachorro5.jpg" alt="cachorro5" />
        <img src="/imagens/cachorro6.jpg" alt="cachorro6" />
        <img src="/imagens/cachorro7.jpg"alt="cachorro7" />
        <img src="/imagens/cachorro8.jpg" alt="cachorro8" />
        <img src="/imagens/cachorro9.jpg" alt="cachorro9" />
        <img src="/imagens/cachorro10.jpg" alt="cachorro10" />
        <img src="/imagens/cachorro11.jpg" alt="cachorro11" />
        <img src="/imagens/gato1.jpg" alt="gato1" />
    </div>
<!-- {/each} -->

<style>

    img{
        max-height: 100%;
    }

</style>