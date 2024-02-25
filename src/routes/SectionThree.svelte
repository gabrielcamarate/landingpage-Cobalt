<div class="section-content">

    <div class="title">
        <h1>Tudo que você precisa.</h1>
        <h1>Nada que você não faça</h1>
    </div>

    <div class="paragraph">
        <p class="paragraph-p">Gestão financeira e visibilidade em um só lugar. Experiência <span class="paragraph-color">um kit de ferramentas flexível</span> que torna cada tarefa muito fácil.</p>
    </div>

    <div class="three-boxes">
        <img src="/box-one.png" alt="Informações ao seu alcance">
        <img src="/box-two.png" alt="Gerenciamento em tempo real">
        <img src="/box-three.png" alt="Alertas comerciais importantes">
    </div>

    <div class="two-boxes">
        <img src="/box-four.png" alt="Conecte todos os seus aplicativos">
        <img src="/box-five.png" alt="Você está no controle">
    </div>
</div>

<!-- =============== CSS =============== -->

<style>
    .three-boxes {
        display: flex;
        justify-content: space-between;
        margin-top: 64px;
    }
    
    .two-boxes {
        display: flex;
        justify-content: space-between;
        margin-top: 32px;
    }

    .section-content {
        width: 1425px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
    }

    .title {
        margin-top: 175px;
    }

    .title > h1 {
        font-family: 'Inter';
        font-style: normal;
        font-weight: 700;
        font-size: 48.2px;
        line-height: 51px;
        letter-spacing: -1.2px;

        background: linear-gradient(135deg, #FFFFFF 0%, #71717A 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
    }

    .paragraph {
        width: 536px;
    }
    
    .paragraph-p {
        /* Com o Cobalt, gerenciar as finanças da sua empresa é fácil, */
        font-family: 'Inter';
        font-style: normal;
        font-weight: 400;
        font-size: 17.9px;
        line-height: 28px;
        color: rgba(161, 161, 170, 0.8);
    }

    .paragraph-color {
        color: #E4E4E7;
    }
</style>