Ferramentas para Big Data
================

<div style="text-align: left">
<img src="Ferramentas_files/ferramentas-01.jpg" width="300"/> Por
Alisson Neimaier e Taiane Schaedler Prass
</div>

## **Apache Hadoop**

![Hadoop Logo](Ferramentas_files/hadoop-logo.jpg) Haddop é uma plataforma de software em Java para computação distribuída e processamento de grandes massas de dados. O Hadoop não é uma ferramenta única, mas sim uma coleção de subprojetos relacionados para computação distribuída, todos eles hospedados pela *Apache Software Foundation*
[(http://hadoop.apache.org/)](http://hadoop.apache.org/), sendo que os mais conhecidos são o MapReduce e o sistema de arquivos distribuídos (HDFS).

É um sistema de armazenamento compartilhado para processamento de grandes volumes de dados através de clusters de computadores (escalabilidade horizontal). O ecossistema Hadoop é composto por 3 módulos principais:

  - **Hadoop Distributed File System** (HDFS):  Responsável pelo armazenamento distribuído.

  - **Hadoop Yarn**: Gerencia os recursos alocados nos clusters, minimizando a sobreposição de uso de recursos de CPU e Memória que são consumidos por outros frameworks presentes no ecossistema hadoop.
  
  - **Hadoop MapReduce**: Modelo de programação para processamento em larga escala. Duas operações são executadas (map e reduce). A função map processa uma série de entradas na forma de chave/valor e gera para cada uma dessas zero ou mais saídas no formato chave/valor. A função de reduce realiza um agrupamento do foi gerado pela função de map podendo gerar um conjunto menor de dados.

MapReduce é um modelo de programação que permite o processamento de dados massivos em um algoritmo paralelo e distribuído que possui duas fases de processamento, Map e Reduce, ambas gerenciadas internamente pelo Hadoop sem intervenção do programador. O HDFS é um sistema de arquivos criado para armazenar arquivos muito grandes de forma
distribuída, escalável e tolerante a falhas. 

Além do MapReduce e do HDFS existem outros subprojetos do Hadoop que oferecem uma série de serviços complementares ou que adicionam abstrações de maior nível. Dentre eles destacam-se:

  - **Avro**: um sistema de serialização de dados que fornece RPCs (*Remote Procedure Calls*) eficientes e independentes de linguagem,     armazenamento persistente de dados, estruturas de dados ricas, entre outros recursos. É muito utilizado com linguagens de programação dinâmicas.

  - **Pig**: uma plataforma para grandes conjuntos de dados que possui uma linguagem de programação de alto nível para realizar a análise desses dados. Possui a infraestrutura necessária para avaliar os programas criados, como um compilador especial que transforma as aplicações desenvolvidas nessa linguagem em uma sequência de programas MapReduce.

  - **HBase**: uma base de dados distribuída, criada para armazenar tabelas muito grandes (milhões de colunas e bilhões de linhas). Trata-se de um modelo de armazenamento orientado a colunas altamente escalável, inserido no contexto de tecnologias NoSQL (*Not Only SQL*).

  - **ZooKeeper**: um serviço centralizado para coordenação de aplicações distribuídas. Mantém informações de configuração das aplicações distribuídas, além de fornecer a sincronização das mesmas.

  - **Hive**: uma espécie de Data Warehouse distribuído, que facilita a utilização de grandes conjuntos de dados em ambientes de armazenamento paralelo. Provê uma linguagem baseada em SQL, chamada HiveQL, que facilita a estruturação e pesquisa dos dados.
    
Algumas ferramentas complementares são: Sqoop, Oozie, Mahout, Flume, etc. Uma descrição dessas ferramentas pode ser encontrada em [https://rogeraoaraujo.com.br/2020/11/12/big-data-ferramentas-e-tecnologias-parte-2/](https://rogeraoaraujo.com.br/2020/11/12/big-data-ferramentas-e-tecnologias-parte-2/)    


## **Referências**

1.  20 Best Data Analytics Software for 2020  
    <https://financesonline.com/data-analytics/>

2.  11 Best Big Data Analytics Tools in 2020  
    <https://www.guru99.com/big-data-analytics-tools.html>

3.  Top 53 Bigdata Platforms and Bigdata Analytics Software  
    <https://www.predictiveanalyticstoday.com/bigdata-platforms-bigdata-analytics-software/>
