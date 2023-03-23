<template>
    <div class="pre-venda-container">
        <div>
            s<TitlePre class="titulo" title="Catarina Rock"></TitlePre>
            <TitlePre class="titulo" title="Festival"></TitlePre>
            <p>Desenvolvemos o Catarina Rock Festival com o objetivo de oferecer às bandas locais uma oportunidade de gerar um evento com o registro audiovisual de seu trabalho.</p>
        </div>
        <div class="btn-group">
            <button class="button">PRÉ-VENDA</button>
            <button class="button">INSCREVER</button>
        </div>
        <div class="social-group">
            <img src="../../public/img/icons/yt.png" alt="">
            <img src="../../public/img/icons/ig.png" alt="">
            <img src="../../public/img/icons/fb.png" alt="">
        </div>
    </div>
</template>

<script>
    import TitlePre from "../atoms/TitlePre.vue";
    export default {
        components: {
            TitlePre
        }
    }

</script>

<style scoped>
    p {
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        color:white;
        font-size: 1.5em;
        text-align: left;
    }

    .pre-venda-container {
        max-width: 40%;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 20px
    }

    .titulo {
        text-align: left;
    }

    .btn-group {
        display: flex;
        padding: 20px;
        gap: 30px
    }

    .button {
    background: linear-gradient(to bottom,  #1a1b1d,  #1a1b1d, #1a1b1d);
    color: white;
    border: none;
    border-radius: 0;
    padding: 15px 30px;
    font-size: 16px;
    transition: all 0.3s ease-in-out;
  }

  .button:hover {
    opacity: 0.8;
    cursor: pointer;
  }

  .social-group {
    display: flex;
    gap: 10px;
  }

  img {
    width: 100%;
    max-width: 50px;
  }
</style>