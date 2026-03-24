📊 Projeto de Engenharia de Dados com AWS S3 e Databricks (Free Edition)
🧠 Visão Geral

Este projeto demonstra um pipeline completo de Engenharia de Dados utilizando serviços em nuvem, com foco em ingestão, armazenamento, processamento e análise de dados.

As principais tecnologias utilizadas foram:

AWS S3 para armazenamento de dados
Databricks Community Edition (Free) para processamento e análise com Apache Spark

🎯 Objetivos

Criar um pipeline de dados simples e funcional na nuvem
Armazenar dados brutos de forma escalável
Processar dados utilizando Spark
Gerar dados transformados prontos para análise

🏗️ Arquitetura do Projeto

Fonte de Dados → AWS S3 (Raw) → Databricks → AWS S3 (Processed)
☁️ Tecnologias Utilizadas
AWS S3
Databricks Community Edition
Apache Spark (PySpark)
Python
📂 Estrutura do Projeto
📁 projeto-engenharia-dados
 ┣ 📂 data
 ┃ ┣ 📂 bronze
 ┃ ┗ 📂 silver
 ┃ ┗ 📂 gold
 ┣ README.md
 
🚀 Como Executar o Projeto
1. Configurar AWS S3
Criar um bucket no S3
Criar pastas:
/bronze
/silver
/gold

Fazer upload dos dados iniciais
2. Configurar Databricks (Free)
Criar conta no Databricks Community Edition
Criar um cluster
Importar notebook ou script

📈 Resultados
Pipeline automatizado
Dados tratados e organizados
Estrutura pronta para escalar

📚 Aprendizados
Criação de Data Lake com S3
Processamento distribuído com Spark
Criação de jobs de dados
Organização de pipelines

🧩 Melhorias Futuras
Orquestração com Airflow
Camadas Bronze / Silver / Gold
Monitoramento de jobs

👨‍💻 Autor: Bruna Felix
Projeto desenvolvido para fins de estudo em Engenharia de Dados.

