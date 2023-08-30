<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>
     <link rel="stylesheet" href="styles.css">
     <style>
        body {
           
            color: white; /* Cor do texto branco para contrastar */
            font-family: Arial, sans-serif; /* Fonte para o texto */
            margin: 0; /* Remover margens padrão */
            padding: 0; /* Remover espaçamento interno padrão */
        }
        
        .menu-item {
            display: flex; /* Usar flexbox para alinhar o ícone e o texto */
            align-items: center; /* Centralizar verticalmente */
            padding: 10px 20px; /* Espaçamento interno */
            border-bottom: 1px solid white; /* Linha separadora entre os itens */
        }

        .menu-item img {
            width: 30px; /* Largura da imagem */
            height: auto; /* Altura automática para manter proporções */
            margin-right: 10px; /* Margem à direita da imagem */
        }
    </style>
</head>
<body>
<h3 style="color: rgb(11, 131, 236);">Portfólio</h3>
    
<header id="home" class="header">
    <img src="img/mf.jpg"  alt="Profile Picture"  width="300" height="300">
    <h1>Tiago Tenorio </h1>
    <p>Desenvolvedor Web</p>
    
</header>
<h3> CONTATO </h3>
<div class="menu-item">
    <img src="img/tel.png" alt="Ícone Telefone">
    Telefone: (123) 456-7890
</div>
<div class="menu-item">
    <img src="img/mail.png" alt="Ícone Email">
    Email: exemplo@email.com
</div>
<div class="menu-item">
    <img src="img/in.png" alt="Ícone LinkedIn">
    LinkedIn: linkedin.com/seuperfil
</div>

<div class="content">
    <section id="about" class="section">
        <h2>Sobre</h2>
        <p>Meu nome é Tiago Tenório Tenho 22 anos , tenho formação técnica em administração e recursos humanos. Atualmente, estou cursando a faculdade de análise e desenvolvimento de sistemas na Descomplica, uma instituição de ensino online. Tenho interesse por tecnologia e gestão de pessoas.</p>
    </section>

    <section id="resume" class="section">
        <h2>Experiências</h2>
        <h3>Experiência como web designer</h3>
        <p>Minha experiência como desenvolvedor e web designer júnior de nível médio me proporcionou uma base sólida para explorar ainda mais as nuances do design web e para continuar crescendo profissionalmente. Estou liberado com as oportunidades futuras de contribuição para projetos empolgantes e aprimorando minhas habilidades em um ambiente dinâmico e criativo.</p>
        
        <h3>Educação</h3>
        <h5>Formação em Técnico em Administração: </h5>
        <p> Concluí com sucesso o curso técnico em administração, o que me proporcionou uma base sólida nos princípios de gestão, organização e operações empresariais. Essa formação me concedeu uma compreensão fundamental do ambiente corporativo e suas dinâmicas.</p>
        <h5> Curso Técnico em Desenvolvimento de Sistemas (Escola Técnica Senador Wilson )</h5>
        <p> Atualmente está no segundo período do curso técnico em desenvolvimento de sistemas na Escola Técnica Senador Wilson Campos. Este programa está equipado com habilidades essenciais em programação, desenvolvimento de software e resolução de desafios técnicos.</p>
        <h5> Faculdade Descomplica (Curso de Analista de Sistemas): </h5>
        <p> Estou no primeiro módulo do curso de Analista de Sistemas na Faculdade Descomplica. Neste ambiente, estou imerso na exploração aprofundada de tópicos relacionados ao desenvolvimento de software, algoritmos e análise de sistemas. Estou animado para desenvolver ainda mais minhas competências nessa área.</p>
    </section><hr><br><br>
    </div>
    </section><hr> <br><br>
    
    <div class="content">
        <section id="about" class="section">
            <section id="portfolio" class="section">
                <h2>Portfólio</h2>
                <div class="carousel">
                    <div><img src="imagem1.jpg" alt="Imagem 1"></div>
                    <div><img src="imagem2.jpg" alt="Imagem 2"></div>
                    <div><img src="imagem3.jpg" alt="Imagem 3"></div>
                </div>
                <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>
        <script>
            $(document).ready(function(){
                $('.carousel').slick({
                    dots: true, // Exibe os pontos de navegação
                    autoplay: true, // Reprodução automática
                    autoplaySpeed: 3000 // Tempo de exibição de cada slide em milissegundos
                });
            });
        </script>
    
        <section id="resume" class="section">
            <h2>Experiências</h2>
            <h3>Experiência como web designer</h3>
            <p>Minha experiência como desenvolvedor e web designer júnior de nível médio me proporcionou uma base sólida para explorar ainda mais as nuances do design web e para continuar crescendo profissionalmente. Estou liberado com as oportunidades futuras de contribuição para projetos empolgantes e aprimorando minhas habilidades em um ambiente dinâmico e criativo.</p>
            
            <h3>Educação</h3>
            <p>Detalhes sobre sua formação educacional.</p>
        </section>
</div>
<section id="endereço" class="section">
    <h2 style="color: aliceblue;">endereço</h2>
    <h3>Mapa</h3>
    <iframe  width="200" height="200" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d31615.950525850054!2d-35.197563998787864!3d-7.895713736935958!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7ab0a2bb8179129%3A0x2ef3298896b68c7a!2sPaudalho%2C%20PE%2C%2055825-000!5e0!3m2!1spt-BR!2sbr!4v1693330825572!5m2!1spt-BR!2sbr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</section>

<footer class="footer">
    <p>&copy; 2023 Meu Portfólio. Tiago tenorio.</p>
</footer>

<script src="scripts.js"></script>
<script>
    const navigationLinks = document.querySelectorAll('.navigation a');
    navigationLinks.forEach(link => {
        link.addEventListener('click', (event) => {
            event.preventDefault();
            const targetId = link.getAttribute('href');
            const targetSection = document.querySelector(targetId);
            if (targetSection) {
                window.scrollTo({
                    top: targetSection.offsetTop,
                    behavior: 'smooth'
                });
            }
        });
    });
</script>


</body>
</html>
