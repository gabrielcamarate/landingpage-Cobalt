<header>
    <div class="light-effect"></div>
    <nav class="navbar">
        <a href="/" class="logo"> <img src="/logo.svg" alt="Icone da Página"> </a>
        
        <div class="flex-blog">
            <a href="/" class="blog">Blog</a>

            <div class="button-navbar">
                <a href="/" class="whitelist">Junte-se à lista de espera</a>
                <span class="border-effect"></span>
            </div>
        </div>
    </nav>
</header>

<!-- ========================= CSS ========================= -->

<style>

    header {
        max-width: 1425px;
        margin: 0 auto;
    }


    .light-effect {
        position: absolute;
        width: 1425px;
        height: 1558.14px;
        
        background: radial-gradient(48% 37% at 50% 0%, rgba(94, 176, 239, 0.5) 0%, rgba(0, 0, 0, 0) 100%);
        mix-blend-mode: normal;
        border-radius: 0px;
        opacity: 0.3;
    }

    .navbar {
        display: flex;
        justify-content: space-between;
        padding-top: 29px;
    }

    a {
        font-size: 13.9px;
        font-weight: 400;
        text-decoration: none;
    }

    .flex-blog {
        display: flex;
        align-items: center;
    }

    .blog {
        background: none;
        color: #D4D4D8;
        margin-right: 20px;
        z-index: 1;
    }

    .button-navbar {
        /* Div [relative] */
        display: flex;
        justify-content: center;
        position: relative;
        padding: 13px;

        background: #09090b38;
        mix-blend-mode: normal;
        box-shadow: 0px 0px 0px 1px rgba(255, 255, 255, 0.1), 0px 0px 0px #FFFFFF;
        border-radius: 9999px;
    }

    .border-effect {
        /* Span [absolute] */
        position: absolute;
        width: 103.49px;
        height: 1px;
        bottom: -1px;
        

        /* Div [relative] */
        background: linear-gradient(90deg, rgba(34, 211, 238, 0) 0%, rgba(34, 211, 238, 0.9) 50%, rgba(34, 211, 238, 0) 100%);
        mix-blend-mode: normal;
        border-radius: 0px;
    }

    .whitelist {
        color: #A1A1AA;
        display: flex;
        justify-content: center;
        
        background: none;
    }
</style>