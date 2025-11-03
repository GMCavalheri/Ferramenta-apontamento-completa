# Ferramenta Completa de Apontamento

Este projeto enorme tem como objetivo criar toda a infraestrutura de apontamento e gestão de horas, de uma empresa software.

São 4 grandes áreas de desenvolvimento:

1. Uma infraestrutura de dados ETL em Python completa, automatizando e tratando toda a cadeia de informações da empresa.

2. Banco de Dados Relacional PostgreSQL servindo de ferramenta para gerar relatórios rápidos e precisos. Utilizando um modelo de estrela com Tabelas Fato e Tabelas Dimensão. 

3. Um Front-End desenvolvido em JavaScript, CSS e HTML, para servir de ferramenta de apontamento de horas pelos colaboradores.

4. Um parte dedicada a relatórios em Microsoft Power BI, que irá analisar os dados consolidados no banco de dados e trazer insights para os tomadores de decisão da empresa. Utilizaremos conhecimentos de Storytelling para melhorar ao máximo, a eficiência desta etapa.

É um projeto longo, primeiro será desenvolvido uma prova de conceito de cada área, antes de partir para a próxima, seguindo à sequência acima.


## Infraestrutura de dados ETL (Python)


O trabalho de ETL foi conduzida no Jupyter Notebook [`tratando_dados_producao.ipynb`](tratando_dados_producao.ipynb). A primeira função abaixo, gera a estrutura banco de dados consolidade

![Python 1](/imagens/Python1.png)

A segunda função atualiza o banco de dados consolidado com os dados do banco de dados em produção. Ele analiza os as linhas que serão inseridas e atualizadas, dando a opção de atualizar ou não as linhas já consolidadas

![Python 2](/imagens/Python2.png)




## Bibliotecas Utilizadas

As principais bibliotecas utilizadas, listadas em [`requirements.txt`](requirements.txt), são:

1. **[pandas](https://pandas.pydata.org/)** - Manipulação e análise de dados.

2. **[jupyter](https://jupyter.org/)** - Ambiente interativo para notebooks.

## Banco de Dados (PostgreSQL) 



## Front-End (JavaScript, CSS, HTML)


## Storytelling (Microsoft Power BI)


## Conclusões

