<template>
    <div id="sobre">
        <img src="../assets/img-logo/logo2.png" />
        <h1> &lsaquo;from the next step /&rsaquo;</h1>
        <p>Profissional na área do desenvolvimento web, especializado(a) em html, css, javascript e vuejs. Proativo(a) e orientado(a) para resultados, busco contribuir com minha experiência em desenvolvimento web front-end. Comprometido(a) com a excelência, estou pronto(a) para integrar uma equipe dinâmica e agregar valor. Possuo Técnico em Contabilidade pela Instituição Federal Sul-Riograndense (2015), Técnico em Informática para Internet pelo Colégio Técnico Industrial de Santa Maria (2016) e Bacharelado em Sistemas de Informação pela Universidade Federal de Santa Maria (2023).</br> Tecnologias e Ferramentas: HTML, CSS, JavaScript, VueJs, Bootstrap, Bootstrap-vue, PHP, Mysql, Wordpress, Woocommerce, Scrum/Kanban, Git/Github, C e Sass.</br> Aprendendo novas linguagens e ferramentas: PrimeVue e Laravel.</p>
    </div>
</template>
<script>

export default {
    
}
</script>
<style lang="scss" scoped>
    @import url('https://fonts.googleapis.com/css2?family=Anek+Telugu:wght@500&family=Rampart+One&display=swap');
    #sobre{
        background: #536976; /* fallback for old browsers */
        background: -webkit-linear-gradient(to right, #292e49, #536976); /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to right,#292e49, #536976); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

        box-shadow: 1px 1px 10px 5px rgba(0, 0, 0, 0.5);
        border-radius: 5px;

        height: 100%;
        width: 100%;
        padding: 1rem;

        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;

        img{
            width: 40%;
            margin: 0 0 2rem 0;

        }
        h1{
            font-family: 'Rampart One', cursive;
            color: white;
            padding: .5rem;
            margin: 0 0 1rem 0;
            font-size: 3.5rem;

        }
        p{
            font-family: 'Anek Telugu', sans-serif;
            color: white;
            padding: 1rem;
            font-size: 1.5rem;
            text-align: center;
            text-align: justify;

        }

    }
/*################################################*/
@media only screen and (max-width: 1560px) {
    #sobre{
        h1{
            font-size: 2.5rem;

        }
        p{
            font-size: 1.2rem;

        }
    }
}
@media only screen and (max-width: 1200px) {
    #sobre{
        img{
            width: 50%;

        }
        h1{
            font-size: 2.3rem;

        }
        p{
            font-size: 1rem;
            
        }
    }
}
@media only screen and (max-width: 992px) {
    #sobre{
        img{
            width: 50%;

        }
    }
}
@media only screen and (max-width: 720px) {
    #sobre{
        img{
            width: 40%;
            margin: 0 0 1rem 0;

        }
        h1{
            font-size: 2rem;

        }
    }
}
@media only screen and (max-width: 481px) {
    #sobre{
        img{
            width: 60%;

        }
        h1{
            font-size: 1.5rem;
            
        }
        p{
            padding: 0;

        }
    }
}
@media only screen and (max-width: 360px) {
    #sobre{
        padding: .2rem;

        img{
            width: 80%;
            margin: 0 0 .8rem 0;

        }
        h1{
            font-size: 1.3rem;
            width: 100%;
            text-align: center;
            padding: .5rem;
            margin: 0 0 .3rem 0;

        }
        p{
            font-size: .9rem;
            width: 100%;
            padding: .5rem;

        }
    }
}
</style>
