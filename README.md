# Projeto de Análise de Progressão da COVID

Projeto com intuito de utilizar práticas de ETL com pyspark, bem como a manipulação de dados, de forma a trazer informações que não foram observadas ou que possam ser de interesse geral.

## Instalação

O projeto foi desenvolvido a partir de um container em [Docker](https://www.docker.com/resources/what-container) e o primeiro passo foi a instalação do [Docker Hub](https://hub.docker.com/). 
Após feito a instalação e efetuado o login, é possível acessar a imagem Docker para Pyspark executando o comando:

```
docker pull jupyter/pyspark-notebook
```

E assim que executado a imagem é possível, então, ter acesso ao container executando, no terminal, o seguinte comando:

```
docker run -it -p 8888:8888 jupyter/pyspark-notebook
```

Desta forma, será apresentado o endereço do localhost com a porta padrão 8888 no qual redireciona para o Jupyter Lab que servirá de uso para o pyspark.

## Recursos

Tutorial completo de utilização do Pyspark com Docker: [Docker + Pyspark](https://medium.com/@chris.sfreitas10/how-to-use-pyspark-and-jupyter-notebook-with-docker-bb89f04ca895)

Dataset disponível em: [Our World in Data](https://ourworldindata.org/explorers/coronavirus-data-explorer?facet=none&Metric=Confirmed+deaths&Interval=7-day+rolling+average&Relative+to+Population=true&Color+by+test+positivity=false&country=~AFG)
