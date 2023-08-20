# Análise de Tendências de Crimes com Dados do FBI

Projeto: Desenvolvimento de um pipeline de análise de dados para explorar tendências de crimes nos EUA e suas correlações com fatores socioeconômicos.

## Etapas de Desenvolvimento

1. **Extração de Dados**:
    - Extração de dados do FBI Crime Data e outras fontes socioeconômicas.
    - Utilização da biblioteca `pandas` para importação e navegação inicial dos dados.

2. **Transformação e Enriquecimento dos Dados**:
    - Limpeza e tratamento dos dados com `pandas`.
    - Enriquecimento dos dados através da combinação de múltiplas fontes.
    - Criação de indicadores e métricas relevantes para análise.

3. **Modelagem com dbt**:
    - Utilização do `dbt` para modelagem e transformação dos dados.
    - Criação de modelos, testes e documentação.

4. **Carregamento no Google BigQuery**:
    - Utilização da biblioteca `google-cloud-bigquery` para carregar os dados transformados no BigQuery.
    - Estruturação dos dados em tabelas e views para análise.

5. **Orquestração com Airflow**:
    - Configuração do Apache Airflow para orquestrar o pipeline de dados.
    - Criação de DAGs para automação e agendamento das tarefas.

## Protótipo do Pipeline

![Pipeline](https://media.licdn.com/dms/image/D4D22AQE_Rf0SFS-pMg/feedshare-shrink_1280/0/1691353538995?e=1694649600&v=beta&t=_EgvKfqvGHxNZccroxbDVdiSuUDX2DxAOnsJQmyspkQ)

## Passo a Passo

Utilizando o `dbt` e Python, os dados são extraídos, transformados e enriquecidos. Posteriormente, são carregados no Google BigQuery para análises mais profundas e visualizações. O Apache Airflow é utilizado para orquestrar todo o processo, garantindo que o pipeline seja executado de forma eficiente e em intervalos regulares.

## Sobre o Desenvolvedor

Tiago Linhares Um louco por conhecimento, apaixonado por tecnologia e dados.

Conheça mais detalhes no [LinkedIn](https://www.linkedin.com/in/tiago-linhares/).

Fique à vontade para se conectar nas redes sociais:

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tiago-linhares/)

[![Blog LinharesCorp](https://img.shields.io/badge/-LinharesCorp%20Blog-%230077B5?style=for-the-badge&logo=blogger&logoColor=white)](https://www.linharescorp.com/blog)
