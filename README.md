# 🔄 Redundância de Arquivos com Azure Data Factory

## 📌 Descrição do Projeto

Projeto prático com foco na criação de um processo completo de redundância de arquivos usando o Microsoft Azure. O objetivo foi transferir dados de um banco SQL on-premises para o Azure Data Lake, convertendo-os em arquivos `.TXT` organizados por camadas (raw/bronze), utilizando o **Azure Data Factory**.

## 🛠️ Tecnologias e Serviços Utilizados

- Azure Data Factory  
- SQL Server (on-premises e Azure SQL)  
- Azure Blob Storage  
- Integration Runtime  
- Azure Data Lake  

## 🔧 O que foi feito

1. Criação da infraestrutura no Azure  
2. Configuração do Integration Runtime para conectar com o SQL on-premises  
3. Criação dos **Linked Services** para acesso ao SQL e Blob Storage  
4. Definição dos **Datasets** para as tabelas e arquivos  
5. Desenvolvimento dos **Pipelines** de extração, transformação e carregamento (ETL)  
6. Armazenamento de arquivos `.TXT` por camadas: raw/bronze  
7. Validação, execução e análise de performance dos pipelines  

## 📷 Prints

> *(Adicione aqui imagens do seu ambiente Azure Data Factory, pipeline criado, execução, e visualização no Blob Storage)*

## 💡 Aprendizados e Insights

- Compreendi a importância de estruturar pipelines reutilizáveis e bem documentados.
- Aprendi como configurar conexões seguras entre ambientes locais e a nuvem.
- Entendi o conceito de camadas (raw, bronze, silver, gold) em arquiteturas de dados modernas.
- Reforcei boas práticas de ETL com foco em performance e organização.

## 🚀 Possibilidades Futuras

- Implementar camada **Silver** com dados tratados.  
- Automatizar execuções com base em triggers.  
- Aplicar validações mais avançadas e logging com Azure Monitor.  
- Integrar com ferramentas de visualização como Power BI.
