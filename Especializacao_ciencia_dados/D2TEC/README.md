# Processamento e Análise de dados usando PySpark com Jupyter Notebook em um cluster AWS EMR
![Solution Stack](https://miro.medium.com/max/720/1*9RM7QQL5QgRqFFCnXVEOTg.png)


Esse projeto foi desenvolvido visando demonstrar o processamento e análise exploratória de dados (EDA) utilizando o **PySpark** em um cluster **AWS EMR** (*Elastic MapReduce*).

## Como está organizado este projeto

 1. Na pasta [dataset](https://github.com/halisson-gomides/IFSP/tree/main/Especializacao_ciencia_dados/D2TEC/dataset) encontra-se o arquivo do conjunto de dados crus utilizados na análise exploratória.
 2. Nesse [Notebook](https://github.com/halisson-gomides/IFSP/blob/main/Especializacao_ciencia_dados/D2TEC/d2tec_final_notebook.ipynb) encontra-se o detalhamento de todo o projeto desenvolvido, com explicações teóricas acerca da composição do Cluster EMR, bem como trechos dos códigos utilizados no processamento da EDA, bem como os resultados de sua execução.
 3. Na pasta [imgs](https://github.com/halisson-gomides/IFSP/tree/main/Especializacao_ciencia_dados/D2TEC/imgs) encontra-se as imagens utilizadas nas explicações do notebook.

## Sobre o AWS EMR
Amazon EMR é a plataforma de big data da Amazon Web Services para processamento de dados, análise interativa e machine learning que usa estruturas de código aberto, como Apache Spark, Apache Hive e Presto. Com o EMR, é possível executar análises de grandes volumes de dados [de forma mais célere](https://aws.amazon.com/blogs/big-data/amazon-emr-introduces-emr-runtime-for-apache-spark/) do que com o Apache Spark padrão.

Através do uso do AWS EMR é possível realizar o processamento de dados distribuídos e análises de hipóteses em grande escala usando algoritmos estatísticos e modelos preditivos para revelar padrões ocultos, correlações, tendências de mercado e preferências dos clientes.
![enter image description here](https://res.cloudinary.com/practicaldev/image/fetch/s--wi-Klep8--/c_limit,f_auto,fl_progressive,q_auto,w_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/08n764po1jnvtvmfwmne.png)

## Sobre o PySpark

**PySpark** é uma API Python para Apache **SPARK** que é denominado como o mecanismo de processamento analítico para aplicações de processamento de dados distribuídos em larga escala e aprendizado de máquina, ou seja, para grandes volumes de dados.
O uso da biblioteca Pyspark possui diversas vantagens:

 - É um mecanismo de processamento distribuído, na memória, que permite
   o processamento de dados de forma eficiente e de características
   distribuída.
 - Com o uso do PySpark, é possível o processamento de dados em Hadoop
   (HDFS), AWS S3 e outros sistemas de arquivos.
 - Possui bibliotecas de aprendizado de máquina e gráficos.
 - Geralmente as aplicações criadas e executadas no PySpark são 100x
   mais rápidas que outras em sistemas de dados conhecidos.

Toda a execução dos scripts é realizada dentro do Apache Spark, que distribui o processamento dentro de um ambiente de cluster que são interligados aos NÓS que realizam a execução e transformação dos dados.


## Referências Bibliográficas

 - [Plataforma de big data - Amazon EMR - Amazon Web Services](https://aws.amazon.com/pt/emr/).
 - [Tutorial: Conceitos básicos do Amazon EMR - Amazon EMR](https://docs.aws.amazon.com/pt_br/emr/latest/ManagementGuide/emr-gs.html).
 - [Projeto Interdisciplinar 2S2021](https://github.com/omarfidelis/PI_2S2021/blob/main/documents/PI_Omar_20211205.pdf). Instituto Federal de Educação, Ciência e Tecnologia de São Paulo - IFSP. Omar Hajime Fidelis.


```
