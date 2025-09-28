<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abordagem Investigativa no Ensino de Biologia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9fafb;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #2563eb;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        main {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            background: white;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        h2 {
            color: #2563eb;
            margin-top: 30px;
        }

        .accordion {
            margin-top: 20px;
        }

        .accordion-item {
            border: 1px solid #ddd;
            border-radius: 8px;
            margin-bottom: 10px;
            overflow: hidden;
            box-shadow: 0 2px 6px rgba(0,0,0,0.05);
        }

        .accordion-header {
            background-color: #f1f5f9;
            cursor: pointer;
            padding: 15px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .accordion-header:hover {
            background-color: #e2e8f0;
        }

        .accordion-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.4s ease, padding 0.3s ease;
            padding: 0 15px;
        }

        .accordion-content p {
            margin: 15px 0;
        }

        .accordion-item.active .accordion-content {
            max-height: 200px;
            padding: 15px;
        }

        figure {
            text-align: center;
            margin: 30px 0;
        }

        figure img {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.15);
        }

        footer {
            margin-top: 40px;
            font-size: 0.9em;
            color: #555;
            padding: 20px;
            background-color: #f1f5f9;
        }

        footer h3 {
            margin-top: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Abordagem Investigativa no Ensino de Biologia</h1>
        <p>Um guia interativo para professores</p>
    </header>

    <main>
        <h2>Principais Etapas</h2>
        <p>Clique em cada etapa para visualizar mais detalhes:</p>

        <div class="accordion">
            <div class="accordion-item">
                <div class="accordion-header">1. Problematização</div>
                <div class="accordion-content">
                    <p>Apresentar uma questão instigante ou um fenômeno biológico que desperte a curiosidade dos estudantes.</p>
                </div>
            </div>

            <div class="accordion-item">
                <div class="accordion-header">2. Levantamento de hipóteses</div>
                <div class="accordion-content">
                    <p>Incentivar os alunos a sugerirem explicações provisórias para o problema proposto.</p>
                </div>
            </div>

            <div class="accordion-item">
                <div class="accordion-header">3. Planejamento da investigação</div>
                <div class="accordion-content">
                    <p>Definir, junto aos estudantes, estratégias, experimentos ou pesquisas bibliográficas para testar as hipóteses.</p>
                </div>
            </div>

            <div class="accordion-item">
                <div class="accordion-header">4. Coleta de dados</div>
                <div class="accordion-content">
                    <p>Realizar a investigação por meio de experimentos, observações ou análise de informações.</p>
                </div>
            </div>

            <div class="accordion-item">
                <div class="accordion-header">5. Análise e interpretação</div>
                <div class="accordion-content">
                    <p>Refletir sobre os resultados obtidos, comparando-os com as hipóteses iniciais.</p>
                </div>
            </div>

            <div class="accordion-item">
                <div class="accordion-header">6. Conclusão e socialização</div>
                <div class="accordion-content">
                    <p>Compartilhar as descobertas, discutindo implicações e novos questionamentos.</p>
                </div>
            </div>
        </div>

        <figure>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/Lab_equipment.jpg/640px-Lab_equipment.jpg" alt="Ensino por investigação em Biologia">
            <figcaption>O ensino investigativo valoriza a experimentação e a análise crítica.</figcaption>
        </figure>

        <footer>
            <h3>Referências</h3>
            <ul>
                <li>CARVALHO, A. M. P. (Org.). <em>Ensino de Ciências por investigação: condições para implementação em sala de aula</em>. São Paulo: Cengage Learning, 2013.</li>
                <li>ZÔMPERO, A. F.; LABURÚ, C. E. A. O ensino de ciências por investigação: histórico, características e desafios. <em>Investigações em Ensino de Ciências</em>, v. 17, n. 3, p. 599-613, 2012.</li>
                <li>BRASIL. Ministério da Educação. <em>Base Nacional Comum Curricular</em> (BNCC). Brasília: MEC, 2018.</li>
            </ul>
        </footer>
    </main>

    <script>
        const items = document.querySelectorAll('.accordion-item');

        items.forEach(item => {
            const header = item.querySelector('.accordion-header');
            header.addEventListener('click', () => {
                item.classList.toggle('active');
            });
        });
    </script>
</body>
</html>
