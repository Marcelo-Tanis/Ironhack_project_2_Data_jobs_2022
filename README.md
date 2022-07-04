# Ironhack_project_2-Data_Jobs
 
Objetivo:

   Este projeto tem como foco apresentar aos interessados ou estudantes dedicados à formação em ciência de dados e em suas diversas especialidades, um resumido cenário geral das oportunidades de emprego ao redor do mundo com as respectivas faixas salariais da profissão, tomando como referência as informações adquiridas entre período do ano de 2020 até o momento.
   Ele se baseia em uma história fictícia porém não menos real, que formula perguntas e respostas sobre o tema em questão.
   
Fontes de pesquisa:
   Foi utilizado como base o data set no formato .csv extraido do site www.kaggle.com,   elaborado por Saurabh Shahane, confome link abaixo: 
   
   https://www.kaggle.com/datasets/saurabhshahane/data-science-jobs-salaries   
   
   O mesmo teve como base as informações extraidas do site de busca de empregos 'ai-jobs.net'.
   
   
   Estrutura:
   
   O projeto foi desenvolvido em duas partes.
   
   
   1) A primeira parte realizada na plataforma jupyter notebook, na linguagem python, e seguindo os princípios 'data pipeline', 
   possibilitando a conexão com a plataforma SQL de banco de dados. Após a extração e a transformação do data set, que incluiu tratamento e limpeza, restaram 211 amostras de emprego ao redor do mundo a serem utilizadas como referência.  As seguintes tabelas do data set foram as relevantes para posterior análise gráfica:
   
   *job_title - tipo de especialização na área de dados
   
   *experience_level -  categoria do profissional  por tempo de experiência
                     EN - Entry Level / junior(< 2 anos de experiência);
                     MI - Middle Level (>= 2 e < 5 anos de experiência);
                     SE - Sênior (>= 5 anos de experiência);
                     Ex - Executivo / Diretor.
                     
   *remote_ratio - proporção de trabalho remoto oferecida na vaga de emprego
                 0 - < 20% do trabalho remoto;
                 50 - >= 20% e < 80% do trabalho remoto;
                 100 - >= 80% do trabalho remoto. 
                 
   *monthly_salary_usd - salário mensal oferecido convertido para o dólar
   
   *work_year - o ano em que houve a contratação: 2020 e 2021/2022
                Os anos de 2021/2022 encontram-se na mesma linha pois o data set utilizado ainda vem sendo atualizado no Kaggle.
               
               
     obs. Nessa primeira parte do projeto foi  também criado um código aplicando a metodologia web scrapping, que extrai uma lista do site de buscas de empregos Indeed (www.indeed.com), com as mais recentes vagas no cargo de analista de dados nível júnior no Brasil. 
   
   
   
   2) A segunda parte do projeto foi desenvolvida na plataforma gráfica Tableau, para a visualização, análise de dados, e a busca das respostas para as perguntas feitas no decorrer da história.
   
   obs:
   * Devido ao grande numero de sub-categorias de empregos(lead, manager, consultant, etc.), a análise foi estruturada em quatro tipos de especialização:
   Engenheiro de dados, analista de dados, cientista de dados e engenheiro de machine learning.
   
   * Alguns outliers (valores salariais muito distantes da média) foram removidos, assim como as medianas salariais foram utilizadas ao invés das médias para aumentar a precisão dos resultados.
   
   * Os países citados estão em destaque não por oferecerem mais oferta de emprego que outros com talvez mais vagas disponíveis, mas sim por estarem abertas a contratação também de estrangeiros, por isso uma maior relevância a nível mundial. Da mesma forma as respectivas médias salariais, que variam proporcionalmente com o custo de vida de cada local.
   
   
   
   
   A história:
   
   Temos uma história e ela tem um começo...   
   
     Um grande amigo, insatisfeito com a sua atual profissão, e não descartando a ideia de se mudar para o exterior e, sabendo que não tenho mais procurado os amigos pois estou mergulhado no bootcamp Ironhack, me convida para tomar um  café e solicitar informações sobre a minha futura nova profissão, que é a de analista de dados.   
     Então ele faz uma série de 9 perguntas. A primeira segue abaixo,
   
   PERGUNTA 1: Vi muitas especializações nessa área de dados e não entendi nada, pode me dar uma rápida noção?
   
   Seguindo o bom senso de qualquer análise fui, antes do encontro, fazer uma pesquisa sobre o tema, já imaginando que seria essa uma possível pergunta inicial:
   
   Resumidamente:
   
   *Engenheiro de dados: Especializado em estrutura de dados. Prepara o material e a base de códigos para as outras áreas de dados.
   *Analista de dados: coleta, trata, analisa os dados, e busca soluções de acordo com as análises.
   *Cientista de dados: trabalha com uma maior gama de informações.Uma visão mais macro, mais planejamento do que a análise imediata em si.
   *Engenheiro de machine learning: trabalha no ramo da inteligência artificial. O desenvolvimento do atendimento virtual ao cliente é um exemplo.
   
   
   
   * As outras 8 perguntas assim como as respostas estão descritas na apresentação gráfica com o Tableau. Segue o link abaixo:
   
   https://public.tableau.com/app/profile/marcelo5344/viz/IRONHACK_PROJECT2-Data_Jobs_jobs_project/Story9-JOBSLOCATIONSHIGHLIGTHS?publish=yes   
   
     
   
   
   
   
   
   
   
