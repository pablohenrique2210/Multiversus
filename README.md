<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre o GOAT da Arte Suave</title>
    <style>
        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
            text-decoration: none;
            border: none;
            outline: none;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        html {
            font-size: 62.5%;
        }

        body {
            width: 100%;
            min-height: 100vh;
            background-color: rgba(0, 0, 196, 0.589);
            color: white;
            padding-top: 80px;
        }

        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            padding: 1.5rem 5%;
            background-color: rgba(0, 0, 100, 0.9);
            filter: drop-shadow(0px 5px 10px rgba(0, 0, 0, 0.3));
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 100;
        }

        .GOAT {
            font-size: 3rem;
            color: white;
            font-weight: 800;
            cursor: pointer;
            transition: 0.5s ease;
        }

        .GOAT:hover {
            transform: scale(1.1);
            color: red;
        }

        nav {
            display: flex;
            gap: 2.5rem;
        }

        nav a {
            font-size: 1.6rem;
            color: white;
            font-weight: 500;
            transition: 0.3s ease;
            padding: 0.8rem 1.5rem;
            border-radius: 5px;
            white-space: nowrap;
        }

        nav a:hover,
        nav a.active {
            color: blue;
            background-color: rgba(255, 255, 255, 0.2);
            border-bottom: 3px solid red;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        section {
            display: none;
        }

        section.active {
            display: block;
        }

        h1 {
            font-size: 3.5rem;
            margin-bottom: 2rem;
            text-align: center;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        h2 {
            font-size: 2.8rem;
            margin: 3rem 0 1.5rem 0;
            color: #ffcc00;
            border-left: 4px solid #ffcc00;
            padding-left: 1rem;
        }

        p {
            font-size: 1.8rem;
            line-height: 1.6;
            margin-bottom: 2rem;
            text-align: justify;
        }

        .image-container {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
            margin: 3rem 0;
        }

        .image-container img {
            max-width: 100%;
            height: auto;
            border: 3px solid white;
            border-radius: 8px;
            flex: 1 1 300px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        ol, ul {
            font-size: 1.8rem;
            margin-left: 3rem;
            margin-bottom: 2rem;
        }

        li {
            margin-bottom: 1rem;
            line-height: 1.5;
        }

        .author {
            font-style: italic;
            font-size: 1.6rem;
            margin-bottom: 3rem;
            text-align: right;
        }

        .quote {
            background-color: rgba(0, 0, 100, 0.3);
            padding: 2rem;
            border-radius: 10px;
            margin: 2rem 0;
            border-left: 5px solid red;
        }

        @media (max-width: 768px) {
            header {
                flex-direction: column;
                padding: 1rem 5%;
            }

            nav {
                flex-wrap: wrap;
                justify-content: center;
                margin-top: 1rem;
                gap: 1rem;
            }

            nav a {
                font-size: 1.4rem;
                padding: 0.6rem 1rem;
            }

            h1 {
                font-size: 2.8rem;
            }

            h2 {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <a href="#" class="GOAT">Roger Gracie</a>
        <nav>
            <a href="#home" class="active">Home</a>
            <a href="#dominio">Domínio em Competições</a>
            <a href="#mentalidade">Mentalidade do Lutador</a>
            <a href="#tecnica">Técnica Impecável</a>
            <a href="#conclusao">Conclusão</a>
        </nav>
    </header>

    <div class="container">
       
        <section id="home" class="active">
            <h1>Roger Gracie: A Perfeição no Jiu-Jitsu e o Legado do Maior de Todos os Tempos</h1>
            <div class="image-container">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQRWMt3a5bd1ZKLai5UiKOLVA9WzuMdNAqzsA&s" alt="Roger Gracie">
                <img src="https://pbs.twimg.com/media/EteuMiiWQAAhw6w.jpg" alt="Roger Gracie competindo">
                <img src="https://a.espncdn.com/i/headshots/mma/players/full/2504982.png" alt="Roger Gracie ESPN">
            </div>
            <p class="author">*Por Pablo Henrique, especial para Gabriel Michael B Augusto*</p>
            <p>No universo do jiu-jitsu, poucos nomes brilham com tanta intensidade quanto o de <strong>Roger Gracie</strong>... </p>
        </section>

       
        <section id="tecnica">
            <h2>Técnica Impecável: Eficiência e Simplicidade</h2>
            <p>Roger Gracie é sinônimo de <strong>jiu-jitsu puro</strong>...</p>
            <ol>
                <li><strong>Montada Dominante</strong>: Roger era mestre...</li>
                <li><strong>Passagem de Guarda Impecável</strong>: ...</li>
                <li><strong>Defesa Inabalável</strong>: ...</li>
            </ol>
            <p>Seu estilo provou que <strong>o básico bem feito é invencível</strong>...</p>
        </section>

      
        <section id="dominio">
            <h2>Domínio Absoluto em Competições</h2>
            <p>Roger não apenas vencia; ele <strong>esmagava</strong> a concorrência...</p>
            <ul>
                <li><strong>10x Campeão Mundial de Jiu-Jitsu</strong>...</li>
                <li><strong>Único lutador a vencer...</strong></li>
                <li><strong>Campeão no ADCC...</strong></li>
                <li><strong>Transição para o MMA...</strong></li>
            </ul>
        </section>

       
        <section id="mentalidade">
            <h2>A Mentalidade do Lutador Perfeito</h2>
            <p>Além da técnica, Roger Gracie personificava a <strong>mentalidade vencedora</strong>...</p>
            <ol>
                <li><strong>Estratégia Inteligente</strong>: ...</li>
                <li><strong>Respeito e Humildade</strong>: ...</li>
                <li><strong>Legado como Professor</strong>: ...</li>
            </ol>
        </section>

        <section id="conclusao">
            <h2>Conclusão: O Padrão Ouro do Jiu-Jitsu</h2>
            <p>Roger Gracie não é apenas um dos maiores; ele é <strong>o padrão</strong>...</p>
            <div class="quote">
                <p>"Eu não tento fazer coisas difíceis. Eu faço o básico melhor do que todo mundo."</p>
                <p><strong>– Roger Gracie</strong></p>
            </div>
        </section>
    </div>

    <script>
        const links = document.querySelectorAll("nav a");
        const sections = document.querySelectorAll("section");

        links.forEach(link => {
            link.addEventListener("click", e => {
                e.preventDefault();

                
                links.forEach(l => l.classList.remove("active"));
                sections.forEach(s => s.classList.remove("active"));

               
                link.classList.add("active");
                const target = document.querySelector(link.getAttribute("href"));
                target.classList.add("active");
            });
        });
    </script>
</body>
</html>
