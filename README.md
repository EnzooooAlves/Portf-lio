<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Portfólio de ENZO ALEXANDRE ALVES DE MOURA</title>
    <style>
        /* Resetando margens e padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Estilos gerais */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            color: #333;
        }

        /* Cabeçalho */
        header {
            background-color: #2b1111;
            color: white;
            text-align: center;
            padding: 40px 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
        }

        header h1 {
            font-size: 32px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        header p {
            font-size: 18px;
            font-style: italic;
        }

        header .profile-photo {
            border-radius: 50%;
            width: 100px;
            height: 100px;
            object-fit: cover;
        }

        /* Container principal */
        .container {
            width: 90%;
            margin: 0 auto;
            padding-top: 40px;
        }

        /* Seções */
        section {
            background-color: white;
            margin-bottom: 30px;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(8, 8, 8, 0.856);
        }

        h2 {
            color: #333;
            font-size: 28px;
            margin-bottom: 20px;
        }

        /* Layout para as seções de Educação e Experiência */
        .education, .experience {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .education-item, .job {
            width: 48%;
            background-color: #f9f9f9;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
        }

        /* Layout para a seção de Projetos */
        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .project {
            width: 48%;
            background-color: #f9f9f9;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
        }

        .project img {
            width: 100%;
            height: 200px; /* Definindo uma altura fixa ou max-height */
            object-fit: cover; /* Garante que a imagem cubra toda a área sem distorção */
            border-radius: 8px;
        }

        /* Contato */
        .contact-info {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
        }

        .contact-info a {
            color: #4CAF50;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        /* Responsividade */
        @media screen and (max-width: 768px) {
            header {
                flex-direction: column;
                text-align: center;
            }

            header h1 {
                font-size: 28px;
            }

            .education-item, .job, .project {
                width: 100%;
            }

            .profile-photo {
                width: 80px;
                height: 80px;
            }
        }
    </style>
</head>
<body>

    <header>
        <!-- Corrigido: Adicionando o atributo 'alt' para acessibilidade -->
        <img src="c:\Users\DISDAL\Downloads\7d279793-2dcb-4232-af4f-085a69113b91.jfif" alt="Foto de Enzo Alexandre Alves de Moura" class="profile-photo">

        <div>
            <h1>ENZO ALEXANDRE ALVES DE MOURA</h1>
            <p>Desenvolvedor Web | Designer | Criativo</p>
        </div>
    </header>

    <div class="container">
        
        <!-- Seção de Sobre Mim -->
        <section id="about">
            <h2>Sobre Mim</h2>
            <p>Olá, me chamo Enzo, um desenvolvedor apaixonado por tecnologia e design.</p>
            <p>Tenho experiência no desenvolvimento de sites e aplicativos web, sempre buscando melhorar a experiência do usuário e aplicar as melhores práticas de desenvolvimento.</p>
        </section>
        
        <!-- Seção de Educação -->
        <section id="education">
            <h2>Educação</h2>
            <div class="education">
                <div class="education-item">
                    <h3>Nome da Universidade</h3>
                    <p><strong>Curso:</strong> Centro universitário do centro oeste-unidesc</p>
                    <p><strong>Período:</strong> 2019 - 2025</p>
                </div>
                <div class="education-item">
                    <h3>Certificação em Desenvolvimento Web</h3>
                    <p><strong>Instituição:</strong> Udemy</p>
                    <p><strong>Ano:</strong> 2023</p>
                </div>
            </div>
        </section>
        
        <!-- Seção de Experiência Profissional -->
        <section id="experience">
            <h2>Experiência Profissional</h2>
            <div class="experience">
                <div class="job">
                    <h3>Desenvolvedor Front-end - Empresa Disdal X</h3>
                    <p><strong>Período:</strong> Janeiro 2023 - Maio 2023.</p>
                </div>
                <div class="job">
                    <h3>Estagiário de Desenvolvimento - Empresa Disdal</h3>
                    <p><strong>Período:</strong> Junho 2023 - Dezembro 2023</p>
                    <p>Apoio na manutenção de sistemas de um site e app.</p>
                </div>
            </div>
        </section>
        
        <!-- Seção de Projetos -->
        <section id="projects">
            <h2>Projetos Destacados</h2>
            <div class="projects">
                <div class="project">
                    <h3>Site de Portfólio</h3>
                    <!-- Corrigido: Usar caminho relativo ou URL correta -->
                    <img src="c:\Users\DISDAL\Pictures\Sem título.png" alt="Projeto 1">
                    <p>Desenvolvimento de um site pessoal para exibição de projetos e habilidades.</p>          
            </div>
        </section>
        
        <!-- Seção de Contato -->
        <section id="contact">
            <h2>Contato</h2>
            <div class="contact-info">
                <p><strong>Email:</strong> enzo.moura@sounidesc.com.br</p>
                <p><strong>Número:</strong> 61 99268-4251</p>
            </div>
        </section>

    </div>

</body>
</html>