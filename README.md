### Olá 👋
Meu nome é José Carlos e muitos me chamam de JC ou de Zé. Trabalho com dados há 9 anos e aqui irei concentrar meus projetos de estudo. Estou graduando em Ciência da Computação e sou pós graduado em Engenharia de dados e, que é a área que venho me desenvolvendo nos últimos dois anos. Antes disso trabalhei no contexto de Dados por muitos anos, e tive a oportunidade de atuar criando Dashboards em Power BI e Excel, bem como modelar Data Marts em SQL Server e criar pipelines de ETL. Atualmente estou focado em desenvolver soluções para Engenharia/Analytics, e uso como tecnologias: Airflow, Python, Pyspark, Docker, Terraform, Kubernetes, AWS, AZURE e GCP e o indispensável SQL, dentre outras que tive pouco contato, como DBT e SNOWFLAKE.
Fique a vontade pra me chamar para trocar ideias sobre dados! <br>

Nos útimos dias tenho trabalhado em um repositório que explora dados das empresas listadas na bolsa de valores. A ideia é coletar informações de fontes diversas e apresentar insights com base nos dados coletados. [Dados Econômicos](https://github.com/josecarlos-dataengineer/DataLakehouse_Dados_Economicos).
A primeira exploração que fiz, foi análise de crescimento de receita nos últimos 5 anos. Abaixo a figura mostra alguns padrões interessantes que mostram o crescimento de receita e também a nota no Reclame Aqui. <br>

![PowerBI](https://github.com/josecarlos-dataengineer/DataLakehouse_Dados_Economicos/blob/main/SQL/imagens/primeira_analise.png) <br>

Os dados apresentados vêm dos portais dados.cvm.gov.br, fundamentus.com.br e fundamentei.com.
Essa primeira análise mostrou:
* No gráfico de dispersão, pode-se notar que o crescimento máximo no eixo X é 60%, e isso aconetece porque estão apresentadas as empresas que possuem nota maior ou igual zero. Muitas empresas cresceram em receita acima de 60%, mas não possuem nota no reclame aqui.
* No filtro de segmento de listagem consta 'na' para alguns casos, e isso acontece porque o left join entre a tabela que tem todos os ticker e a tabela que tem os segmentos não encontrou relacionamento com a chave cnpj. Para este caso, buscarei uma fonte complemetar ou mais completa.

A arquitetura dessa análise é apresentada abaixo: <br>
![arquitetura]([https://github.com/josecarlos-dataengineer/DataLakehouse_Dados_Economicos/blob/main/SQL/imagens/primeira_analise.png](https://github.com/josecarlos-dataengineer/DataLakehouse_Dados_Economicos/blob/main/imagens/arquitetura_an%C3%A1lise.PNG)) <br>

### Tecnologias que conheço.
![Skills](https://github.com/JC3008/DataEngineering_Kubernetes/blob/dev/images/Skills.PNG)




<!--
**josecarlos-dataengineer/josecarlos-dataengineer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
