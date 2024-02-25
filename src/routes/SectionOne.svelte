<section class="section-content">
    <div class="mx-auto">
        <div class="relative-div">
            
            <div class="title">
                <h1>Liberte o poder das</h1>
                <h1>finanças intuitivas</h1>
            </div>

            <div class="paragraph">
                <p>Diga adeus às ferramentas financeiras ultrapassadas. Todo pequeno empresário,</p>
                <p>independentemente da experiência, agora podem gerenciar seus negócios como um profissional. Simples.</p>
                <p>Intuitivo. E nunca chato.</p>
            </div>

            <div class="container-more-informations">
                <div class="button">
                    <a href="/" class="whitelist">Junte-se à lista de espera</a>
                    <span class="border-effect"></span>
                </div>
                
                <div class="ask-more">
                    <a href="/">Saber mais</a>
                    <img src="/arrow-bottom.svg" alt="Seta apontada pra baixo">
                </div>
            </div>
        </div>
        
        <div class="perspective-div">
            <div class="contents">

                <div class="img-leadborad">
                    <img src="/image-leadboard.svg" alt="Imagem de um Leadboard">
                </div>

            </div>
        </div>
    </div>
</section>


<!-- ========================= CSS ========================= -->

<style>
    .img-leadborad {
        display: flex;
        flex-direction: column;
        margin-top: 100px;
    }

    .section-content {
        width: 1425px;
        margin: 0 auto;
    }

    .title {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-top: 105px;
    }

    .title > h1 {
        font-family: 'Inter';
        font-style: normal;
        font-weight: 700;
        font-size: 71.9px;
        line-height: 77px;
        letter-spacing: -1.8px;

        background-image: linear-gradient(135deg, #ffffff 0%, #71717A 100%);
        color: transparent;
        -webkit-background-clip: text;
        background-clip: text;
        z-index: 0;
    }

    .paragraph {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-top: 24px;
    }

    .paragraph > p {
        font-family: 'Inter';
        font-style: normal;
        font-weight: 500;
        font-size: 19.8px;
        line-height: 32px;

        color: #A1A1AA;
    }

    .container-more-informations{
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .button {
        width: 195px;
        height: 36px;

        display: flex;
        justify-content: center;
        position: relative;

        padding: 12px;
        margin-top: 40px;

        background: #09090b;
        mix-blend-mode: normal;
        box-shadow: 0px 0px 0px 1px rgba(255, 255, 255, 0.1), 0px 0px 0px #FFFFFF;
        border-radius: 999px;
    }

    .border-effect {
        position: absolute;
        width: 103.49px;
        height: 1px;
        bottom: -1px;
        
        background: linear-gradient(90deg, rgba(34, 211, 238, 0) 0%, rgba(34, 211, 238, 0.9) 50%, rgba(34, 211, 238, 0) 100%);
        mix-blend-mode: normal;
        border-radius: 0px;
    }

    .whitelist {
        font-family: 'Inter';
        font-style: normal;
        font-weight: 400;
        font-size: 13.9px;
        line-height: 24px;
        
        color: #A1A1AA;
        text-decoration: none;

        display: flex;
        align-items: center;
    }

    .ask-more {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .ask-more > a {

        font-family: 'Inter';
        font-style: normal;
        font-weight: 400;
        font-size: 13.9px;
        line-height: 24px;
        color: #A1A1AA;
        text-decoration: none;
        margin-top: 40px;
        margin-bottom: 5px;

        background: none;
        z-index: 1;
    }

    .ask-more > img {
        width: 18px;
        height: 18px;
    }
</style>