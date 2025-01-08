# Data Lakehouse BI

**Data Lakehouse BI** é um projeto completo **End-to-End** de uma solução de dados, com foco em atender as necessidades de uma organização de médio a grande porte em relação a **dados**, **Business Intelligence (BI)**, **relatórios** e **Machine Learning**. O projeto simula desde a ingestão de dados até a criação de um **lakehouse** estruturado para BI, visando gerar insights valiosos para a tomada de decisão.

A solução abrange a criação de pipelines de dados em camadas, proporcionando dados limpos e prontos para análise e aprendizado de máquina. O projeto também inclui automação para o envio de relatórios, integrando diferentes componentes e processos para uma solução completa.

## Características principais

- **Ingestão de Dados**: Dados são ingeridos automaticamente e transformados usando AWS Glue, Glue Catalog e Glue Jobs.
- **Lakehouse para BI**: Organize os dados em camadas e utilize o formato **Iceberg** para estruturar os dados, permitindo análises e geração de relatórios para BI.
- **Machine Learning**: Preparação dos dados para treinamento de modelos de aprendizado de máquina, com o objetivo de gerar insights preditivos.
- **Automação de Relatórios**: Envio automatizado de relatórios por e-mail para stakeholders, garantindo que as partes interessadas recebam atualizações de dados com frequência e precisão.

## Boas Práticas Aplicadas

### Gestão Ágil de Projetos
Utilização de metodologias ágeis como **Kanban** para organizar e priorizar tarefas de forma iterativa e incremental, garantindo que o progresso seja monitorado e que o foco esteja sempre nas entregas mais importantes. Link para área de trabalho no Trello : https://trello.com/b/4cWQtttG/projeto-dados

### CI/CD
Implementação de pipelines de **Integração Contínua (CI)** e **Entrega Contínua (CD)** para garantir automação robusta, consistência no desenvolvimento e um fluxo de trabalho eficiente. Isso ajuda a manter o código limpo e a melhorar a colaboração entre as equipes.

### Cybersecurity e LGPD
A conformidade com as melhores práticas de **segurança cibernética** e as regulamentações da **Lei Geral de Proteção de Dados (LGPD)** é fundamental para garantir a integridade e a privacidade dos dados. O projeto foi estruturado para seguir essas práticas desde o início, promovendo a proteção dos dados pessoais e a segurança da informação.

### Padrão de Commits
Uso de um **padrão de commits** organizado e estruturado para garantir clareza e rastreabilidade das mudanças feitas no código. Isso facilita a colaboração e a revisão de código, além de melhorar a manutenção do repositório.

## Tecnologias Utilizadas

- **AWS Glue**: Para orquestrar a ingestão e transformação de dados.
- **AWS S3**: Para armazenar dados brutos e processados.
- **AWS Lambda**: Para automação e integração de processos.
- **Iceberg**: Para criar um data lakehouse escalável e de fácil manutenção.
- **Machine Learning (Frameworks a serem definidos)**: Para análise de dados preditivos.
- **Git**: Para controle de versão e colaboração.

## Estrutura do Projeto

A estrutura do projeto é organizada em diferentes camadas para garantir flexibilidade e escalabilidade:

1. **Camada de Ingestão**: Onde os dados são ingeridos de fontes externas (por exemplo, arquivos CSV).
2. **Camada de Transformação**: Onde os dados são processados, limpos e estruturados usando AWS Glue e Glue Jobs.
3. **Camada de Armazenamento**: Dados estruturados são armazenados no formato **Iceberg** em um **data lake**.
4. **Camada de Análise**: Preparação dos dados para análise de BI e aprendizado de máquina.
5. **Camada de Automação**: Envio automatizado de relatórios e resultados para stakeholders.

## Como Usar

### Pré-requisitos

1. Conta na **AWS** com permissões para acessar **S3**, **Glue** e **Lambda**.
2. Ferramentas de linha de comando como **AWS CLI** configuradas corretamente.
3. Acesso ao repositório para obter o código-fonte e configurá-lo localmente.

### Passos para Implementação

1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/caiohmb/data-lakehouse-bi.git
