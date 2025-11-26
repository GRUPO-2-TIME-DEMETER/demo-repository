# Sprint 1
Desenvolvimento de um portal online para análise de dados da cadeia alimentícia do Vale do Paraíba. Foram criados o Backlog, Dashboard, 5W2H, fluxograma, gráfico de Gantt e apresentações por sprints, com melhorias implementadas após o feedback do cliente.

## Fluxograma
![image](https://github.com/user-attachments/assets/98f62148-25d6-476e-94df-a0d7cf936fc1)

## Backlog
<img width="994" height="577" alt="image" src="https://github.com/user-attachments/assets/a78cd386-24cd-4d24-a2f8-a158247e74f0" />

## Dashboard
<img width="1098" height="619" alt="image" src="https://github.com/user-attachments/assets/d1627dfc-4b26-4898-ab12-564af82d91ca" />

## Gantt
<img width="1090" height="608" alt="image" src="https://github.com/user-attachments/assets/3bd08a4f-ccee-488c-9d35-41a9e279be54" />

# Sprint 2

## User Storys
![image](https://github.com/user-attachments/assets/2f5ef5ea-3729-4b41-a620-2b6d94c0a32d)

## Dashboard
![image](https://github.com/user-attachments/assets/3c834595-0091-4ca0-bd1d-106acf83c189)

![image](https://github.com/user-attachments/assets/fbd73bd0-d0a8-4f9f-b15b-7369fcbb0067)

![image](https://github.com/user-attachments/assets/ee79d829-e12c-4c57-b1e5-53a5ccdc78c1)

![image](https://github.com/user-attachments/assets/77b5e80a-c082-4b71-a4bc-faccf124bd7e)

## Dados 
![image](https://github.com/user-attachments/assets/f59c4ee3-2392-4542-b1cc-9c54cd06d71a)
Os dados foram extraídos da plataforma Comex Stat e tratados utilizando a linguagem Python, com apoio da biblioteca Pandas. Durante o processo, foram filtrados especificamente os 39 municípios pertencentes ao Vale do Paraíba, garantindo que somente informações da região fossem consideradas. Além disso, os códigos SH2 e SH4 dos produtos foram padronizados, reorganizados e categorizados conforme a tabela oficial de classificação, permitindo separar corretamente importações e exportações e preparar os arquivos para uso no Power BI.

# Sprint 3

## User Storys
![image](https://github.com/user-attachments/assets/61de895e-39d3-4a39-9d74-f7075f914277)


## Dashboard
![image](https://github.com/user-attachments/assets/39190933-739d-4688-aace-cee5343ed3d8)

![image](https://github.com/user-attachments/assets/3e95036a-c75b-42ff-aa65-a00cb3073e53)

## Dados
![image](https://github.com/user-attachments/assets/0a54f0ba-600f-4a3f-8a9d-47fc368897af)
Após o tratamento inicial, os dados de importações e exportações foram consolidados e padronizados em arquivos finais no formato CSV. Os produtos foram filtrados de acordo com os códigos SH4 presentes na tabela oficial, respeitando as regras específicas para importações (excluindo os grupos indesejados) e agrupando os produtos nas exportações conforme seus grupos alimentares. Os nomes dos países e dos municípios foram devidamente convertidos para facilitar a interpretação e análise, e colunas desnecessárias foram removidas para manter apenas informações relevantes. Com isso, os arquivos finais estão prontos para serem carregados no Power BI, permitindo visualizações claras, consistentes e alinhadas ao objetivo do projeto.

# Aprendizado por Projeto Integrado (API) - Template

Mapeamento do ecossistena regional industrial - Cadeia alimentícia

# Índice
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Equipe](#Equipe)
* [Backlog do produto](#Product-Backlog)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Registro das Sprints](#Registro-das-Sprints)

# Projeto (API) 
Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentada nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil. 
Uso de estratégias para entender o problema, conceber uma solução viável ao desenvolver e implementar o MVP seguido de sua operação (CDIO). 
Os resultados dos projetos devem obedecer ao Aviso Legal disponível no site da Fatec SJC com definição das datas do kickoff e das sprint.

# Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Manuela Carmona Gomes        |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)              |
| Scrum Master  | Camila Lima Pereira|      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)     |
| Team Member   | Kauane Batista dos Santos              |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)        |
|  Team Member  | Felipe Ribeiro de Oliveira                 |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)        |
|  Team Member  | Anna Caroline Pereira                 |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)   |



# Product Backlog

| Rank | Prioridade | User Story                                                                                                                                              | Estimativa | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
| 1    | Alta       |Como gestor público, quero visualizar um protótipo do painel analítico da região, para entender quais indicadores de comércio serão monitorados.         |    12h     |    1   |
| 2    | Alta       |Como gestor público, quero ver representações gráficas dos principais indicadores de exportação e importação, para ter uma visão inicial do comportamento comercial da região.|  10h     |    1   |
| 3    | Média      |Como gestor público, quero que o protótipo apresente os setores industriais mais relevantes da região, para direcionar a análise dos próximos levantamentos de dados.            |     6h     |    1   |
| 4    | Alta       |Como gestor público, quero acessar dados reais de exportação e importação da cadeia produtiva alimentícia da região, para analisar o desempenho comercial com base em informações confiáveis.                                                                                                                                                         |    10h     |    2   |
| 5    | Alta       |Como gestor público, quero filtrar os dados por cidade e por tipo de produto (SH2), para personalizar m8inha análise e comparar diferentes contextos.    |     8h     |    2   |
| 6    | Alta       |Como gestor público, quero visualizar os municípios que mais exportam e importam, para identificar polos econômicos e tendências locais.                 |     8h     |    2   |
| 7    | Média      |Como gestor público, quero cunsultar o produto mais exportado da região, para entender a vocação produtiva local e orientar políticas industriais.       |     6h     |    2   |
| 8    | Alta       |Como gestor público, quero acessar dados detalhados no nível SH4, para ter uma compreensão mais precisa sobre os produtos comercializados na região.     |    12h     |    3   |
| 9    | Alta       |Como gestor público, quero visualizar variações de aumento ou queda nas exportações e importações, para detectar mudanças significativas no comportamento do mercado alimentício regional.                                                                                                                                                         |     8h     |    3   |
| 10   | Média      |Como gestor público, quero uma análise para entender os motivos dessas variações (aumento ou queda), para tomar decisões mais estratégicas sobre incentivos e políticas públicas.                                                                                                                                                         |    10h     |    3   |
