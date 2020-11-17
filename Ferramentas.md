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

Algumas ferramentas complementares são: Sqoop, Zookeeper, Oozie, Pig, Hive, Mahout, HBase, Flume, etc. Uma descrição dessas ferramentas pode ser encontrada em [https://rogeraoaraujo.com.br/2020/11/12/big-data-ferramentas-e-tecnologias-parte-2/](https://rogeraoaraujo.com.br/2020/11/12/big-data-ferramentas-e-tecnologias-parte-2/)

MapReduce é um modelo de programação que permite o processamento de
dados massivos em um algoritmo paralelo e distribuído que possui duas
fases de processamento, Map e Reduce, ambas gerenciadas internamente
pelo Hadoop sem intervenção do programador. O HDFS é um sistema de
arquivos criado para armazenar arquivos muito grandes de forma
distribuída, escalável e tolerante a falhas.

Além do MapReduce e do HDFS existem outros subprojetos do Hadoop que
oferecem uma série de serviços complementares ou que adicionam
abstrações de maior nível. Dentre eles destacam-se:

  - **Avro**: um sistema de serialização de dados que fornece RPCs
    (*Remote Procedure Calls*) eficientes e independentes de linguagem,
    armazenamento persistente de dados, estruturas de dados ricas, entre
    outros recursos. É muito utilizado com linguagens de programação
    dinâmicas.

  - **Pig**: uma plataforma para grandes conjuntos de dados que possui
    uma linguagem de programação de alto nível para realizar a análise
    desses dados. Possui a infraestrutura necessária para avaliar os
    programas criados, como um compilador especial que transforma as
    aplicações desenvolvidas nessa linguagem em uma sequência de
    programas MapReduce.

  - **HBase**: uma base de dados distribuída, criada para armazenar
    tabelas muito grandes (milhões de colunas e bilhões de linhas).
    Trata-se de um modelo de armazenamento orientado a colunas altamente
    escalável, inserido no contexto de tecnologias NoSQL (*Not Only
    SQL*).

  - **ZooKeeper**: um serviço centralizado para coordenação de
    aplicações distribuídas. Mantém informações de configuração das
    aplicações distribuídas, além de fornecer a sincronização das
    mesmas.

  - **Hive**: uma espécie de Data Warehouse distribuído, que facilita a
    utilização de grandes conjuntos de dados em ambientes de
    armazenamento paralelo. Provê uma linguagem baseada em SQL, chamada
    HiveQL, que facilita a estruturação e pesquisa dos dados.

## **Apache Spark**

É um sistema de cluster para processamento de dados em larga escala. É
possível fazer análise em bancos de dados “quase” instantaneamente
(Stream Processing) ou em dados que já foram coletados a mais tempo
(Batch Processing).

A forma como o Spark Streaming funciona é dividindo o streaming em lotes
(chamados micro lotes) em um intervalo predefinido (N segundos) e, em
seguida, trata cada lote de dados como arquivosResilient Distributed
Datasets (RDDs).

Sua base é o Hadoop HDFS, mas pode ser usado com Cassandra, HBase e
MongoDB, também com as linguagens R, Python e Scala.

Sua maior funcionalidade seria substituir o MapReduce, pois é 100x mais
rápido em memória e 10x em disco.

É possível desenvolver API’s (Interface de Programação de Aplicativos)
em Java, Scala, Python e R.

Integrado ao SQL para manipulação de dados, tem uma biblioteca de
algoritmos de machine learning (MLlib) e uma de gráficos (GraphX).

## **Microsoft HDInsight**

É um serviço do Hadoop e Spark na nuvem. Uma plataforma em que é
possível <span style="color: #0000ff;">lidar</span> com os dados
utilizando diversas aplicações de forma integrada.

## **MongoDB**\*

Banco de dados open source. NoSQL database. Armazena documentos num
formato parecido com json.

## **Plotly**\*

<span style="color: #0000ff;">FAZ UNS GRÁFICO BONITO.</span>

## **Samoa**

Conjunto de algoritmos para data mining e machine learning em “tempo
real”. É possível desenvolver outros algoritmos. Roda em Apache Storm,
S4, Samza e Flink.

## **Lumify (Pago)**

Feito para visualização de dados em 2D ou 3D, mais baseado em dados de
texto, imagens e vídeos.

<https://www.youtube.com/watch?v=Uf9-YhnwvNY>

## **Machine Learning Libraries**

Spark (MLib): <https://spark.apache.org/docs/latest/ml-guide.html>

Flink (FlinkML): parece ter sido descontinuada(?)

Samoa: <https://samoa.incubator.apache.org/documentation/Home.html>

<https://data-flair.training/blogs/hadoop-vs-mongodb/> -\> Comparação
MongoDB vs Hadoop

<https://i2.wp.com/opensourceforu.com/wp-content/uploads/2018/03/Table-1-Comparison-of-teh-best-Big-Data-frameworks-2.jpg?ssl=1>
-\> Tabela comparative dos Frameworks Apache (Hadoop, Spark, etc.)

<https://www.researchgate.net/publication/329239211_Big_Data_Analytics_Technologies_and_Platforms_a_brief_review>
-\> Análise tecnologias de big data UFCE

## **Google Analytics**

Ferramenta “gratuita” do google que analisa as informações sobre os
visitantes do seu site.

<span style="color: #FF3346;">Porque gratuita está entre aspas?</span>

## **Sisense (pago)**

Ferramenta para visualização de dados de uma organização.

  - Pega dados de diversas fontes, Facebook, Google, etc.
  - Bot que responde a perguntas em inglês para facilitar o acesso. Ex:
    “Qual o nosso lucro mensal com clientes na China?”.
  - Ferramenta de ML que detecta anomalias nos dados (?)

## **Looker (pago)**

Ferramenta para visualização de dados de uma organização.

  - Pega dados de diversas fontes, Facebook, Google, etc.
  - Pode ser usada com R e Python
  - Ferramentas como agendamento para analisar os dados e manda-los por
    email em formatos especificas e datas específicas para ajudar no
    controle das empresas.

## **Periscope (pago)**

Ferramenta para visualização de dados de uma organização.

  - Programável em SQL, com ferramentas para facilitar a programação
    (autocompletar palavras, sugestões, etc.)
  - Visualização simples dos dados, com ferramentas para enviar
    relatórios e agendar análise de dados.
  - Os dados são analisados em clusters oferecidos pelo software.

## **Zoho Analytics (pago)**

“O Zoho Analytics (anteriormente, Zoho Reports) é um software de BI e
análise de dados que permite que você crie relatórios e painéis de
dados atraentes e informativos em minutos.”

## **Yellowfinbi (pago)**

A strategic, enterprise suite of BI and analytics products that change
the way you discover and share insights so you can make the best
decisions and act on changes in your data, faster.

Diferenciais: Pode-se incluir inteligência artificial nas análises

## **Domo (pago)**

Ferramenta para visualização de dados de uma organização.

Pega dados de diversas fontes, Facebook, Google, etc.

## **IBM**

  - **IBM Analytics:** Visualização de dados para uma organização
  - **IBM Cognos:** Visualização de dados para uma organização
  - **IBM Watson:** IA que “analisa os dados pra ti” a partir de
    perguntas em inglês.

## **Matlab**

Várias ferramentas de Machine learning e outros algoritmos já prontas,
além da possibilidade de escrever outras funções.

Integração com sistemas de outras empresas, clusters e nuvens.

Suporta imagens, vídeos e outros tipos de dados.

## **SAP**

Visualização de dados para uma organização

## **Referências**

1.  20 Best Data Analytics Software for 2020  
    <https://financesonline.com/data-analytics/>

2.  11 Best Big Data Analytics Tools in 2020  
    <https://www.guru99.com/big-data-analytics-tools.html>

3.  Top 53 Bigdata Platforms and Bigdata Analytics Software  
    <https://www.predictiveanalyticstoday.com/bigdata-platforms-bigdata-analytics-software/>
