# Big Data Introduction

## História e Evolução de Data Analitycs 

A análise de dados tem suas raízes há séculos, mas seu desenvolvimento moderno começou a partir do século 20, à medida que a coleta e o processamento de dados se tornaram mais sistematizados. Inicialmente, os dados eram analisados manualmente por estatísticos para encontrar padrões em amostras pequenas. Com o avanço da tecnologia, a capacidade de coletar e processar dados cresceu exponencialmente, levando à criação de sistemas automatizados para lidar com volumes maiores e mais complexos de dados.

### Principais Marcos na Evolução de Data:

1. **Análise Estatística Tradicional** (séculos XIX e XX): <br>
    No início, a análise de dados era puramente estatística. Técnicas como a regressão linear e a análise de variância foram desenvolvidas para ajudar cientistas e matemáticos a entender padrões em pequenas amostras de dados.

2. **Década de 1960 - Surgimento dos Primeiros Bancos de Dados**: <br>
    O advento dos computadores permitiu que empresas começassem a armazenar dados de forma digital. Surgiram os primeiros **bancos de dados relacionais** (RDBMS), como o **Sistema de Gestão de Banco de Dados** (DBMS), que revolucionou a forma como as empresas gerenciavam e recuperavam informações.

3. **Anos 1980 - Business Intelligence (BI)**: <br>
   O conceito de **Business Intelligence** surgiu, permitindo que empresas começassem a usar relatórios baseados em dados históricos para tomar decisões estratégicas. Ferramentas de BI forneciam dashboards e relatórios para ajudar na análise e visualização de dados.

4. **Década de 2000 - Big Data e Armazenamento Massivo**: <br>
   Com o crescimento da internet, redes sociais e dispositivos móveis, o volume de dados gerados começou a crescer exponencialmente. Surgiu o conceito de **Big Data**, referindo-se a conjuntos de dados grandes e complexos que não podiam ser gerenciados por métodos tradicionais de banco de dados. **Hadoop** e **MapReduce** foram desenvolvidos para processar esses grandes volumes de dados em sistemas distribuídos.

5. **2010s - Data Science e Machine Learning**: <br>
   O campo de **Data Science** começou a se expandir, combinando análise de dados, estatísticas e computação. Ferramentas de **Machine Learning** se tornaram comuns, permitindo que algoritmos aprendessem automaticamente com os dados e fizessem previsões, sem a necessidade de programação explícita para cada cenário.

6. **Atualidade - Inteligência Artificial e Análise Preditiva**: <br>
   O uso de **Inteligência Artificial (IA)** e **Deep Learning** trouxe avanços significativos para a análise de dados, com aplicações em áreas como reconhecimento de imagens, processamento de linguagem natural e sistemas de recomendação. **Análise Preditiva** e **Análise Prescritiva** se tornaram comuns em empresas que desejam não apenas entender dados passados, mas também prever tendências futuras e automatizar decisões.

-----

## Oque é Big Data?

 Big Data refere-se ao grande volume de dados, estruturados,semi-estruturados e não estruturados, que são gerados 
continuamente em diversas fontes, como redes sociais, dispositivos conectados (IoT), transações financeiras, sensores 
em tempo real,etc. Esses dados são gerados em grande velocidade, em diferentes formatos e de maneira massiva, tornando
seu processamento e análise um desafio para métodos e ferramentas tradicionais.

-----

### Os 5V's

## Volume
SQL (PostgreSQL,MYSQL,SQLserver) e No-SQL (MongoDB, DocumentDB, DynamoDB)
Data-Lake (AWS S3 e Azure Blob)
Data-Warehouse (SnowFlake, AWS RedShift, Doris)
Data-LakeHouse
Delta-Lake e Delta-LakeHouse

## Velocidade
Processamento em Streams, Batch e micro-batch

## Variedade
Dado estruturado, não estruturado e semi-estruturado

## Veracidade
Manipulação de dados
Governança de dados

## Valor
Data Viz
Machine Learning

-----
### Data ingestion
-ETL
-ELT

-----

### Open Table Format

blablabla


### Principais Inovações Tecnológicas:

**Bancos de Dados Relacionais (RDBMS)**:

 O lançamento de sistemas como **Oracle**, **IBM DB2** e **Microsoft SQL Server** na década de 1970 e 1980 trouxe uma 
forma organizada de armazenar e consultar dados. A linguagem **SQL** tornou-se o padrão para gerenciar dados 
estruturados.

**Armazenamento Distribuído**:

 Nos anos 2000, sistemas como o **Hadoop Distributed File System (HDFS)** surgiram para lidar com grandes volumes de 
dados, fragmentando-os em pequenos blocos e armazenando-os em múltiplos servidores. Isso possibilitou a 
escalabilidade no armazenamento de dados massivos.

**Processamento Distribuído**:

 O modelo **MapReduce**, desenvolvido pela Google, permitiu que dados fossem processados de forma paralela e distribuída 
em grandes clusters de computadores. Esse modelo foi essencial para lidar com o volume e a complexidade do Big Data.

**Data Warehousing e Data Lakes**:

 Ferramentas como o **Google BigQuery**, **Snowflake** e **Amazon Redshift** permitem a criação de **Data Warehouses**, 
onde dados estruturados são organizados para consultas analíticas rápidas. Já os **Data Lakes** (ex: **Amazon S3**, 
**Azure Data Lake**) permitem o armazenamento de dados brutos (estruturados e não estruturados), que podem ser 
processados posteriormente conforme a necessidade.

**Frameworks de Big Data**:

 Além de Hadoop, o **Apache Spark** surgiu como uma plataforma mais rápida e eficiente para processar grandes volumes de 
dados. Ele suporta processamento em batch e em tempo real, e se tornou amplamente utilizado em ambientes de análise de 
dados.

**Machine Learning e IA**:

 Bibliotecas e frameworks como **TensorFlow**, **PyTorch** e **Scikit-learn** facilitaram o desenvolvimento de 
algoritmos de **Machine Learning**. Isso permitiu que cientistas de dados criassem modelos preditivos e de aprendizado automático com mais eficiência.

**Ferramentas de Visualização de Dados**:
   
 Ferramentas como **Tableau**, **Power BI** e **Looker** tornaram a visualização de dados mais acessível, permitindo 
que usuários de negócios interpretassem e explorassem os dados com facilidade. A visualização de dados tornou-se uma 
parte essencial do processo analítico.

**Nuvem e Computação Distribuída**:

 A chegada da **nuvem** permitiu que empresas armazenassem e processassem dados de forma mais econômica e escalável.  
Serviços como **Amazon Web Services (AWS)**, **Google Cloud Platform (GCP)** e **Microsoft Azure** oferecem ferramentas 
integradas para análise de dados, desde o armazenamento até o processamento e visualização.

**Data Governance e Segurança**:
   
 Com a crescente quantidade de dados, a **governança de dados** e a segurança se tornaram prioridades. Regulamentações 
como **GDPR** (Regulamento Geral sobre a Proteção de Dados) e **LGPD** (Lei Geral de Proteção de Dados) surgiram para 
proteger a privacidade dos indivíduos e garantir que as empresas manuseiem os dados de maneira ética e segura.

-----

### Tendências Futuras:

1. **DataOps**:
 A prática de **DataOps** está crescendo como um conjunto de metodologias e ferramentas para integrar a engenharia de 
dados, ciência de dados e operações de TI. Ele permite uma maior automação e agilidade nos processos de análise de dados.

2. **Análise em Tempo Real**:
 Com o crescimento de dispositivos conectados e Internet das Coisas (IoT), a demanda por **análise de dados em tempo 
real** está crescendo. Tecnologias como **Apache Flink** e **Kafka Streams** permitem o processamento de streams de 
dados em tempo real, o que será cada vez mais essencial para a tomada de decisões imediata.


----- 
