# Projeto de Previsão de Vendas de Sorvete com Machine Learning 🍦📊

Este projeto tem como objetivo desenvolver um modelo de Machine Learning para prever as vendas de sorvete com base na temperatura do dia. O modelo será treinado, gerenciado e implantado utilizando o Azure Machine Learning (AML) e outras ferramentas da plataforma Azure.

## Visão Geral do Projeto

### Cenário
Imagine que você é proprietário de uma sorveteria chamada Gelato Mágico, localizada em uma cidade litorânea. A quantidade de sorvetes vendidos diariamente tem uma forte correlação com a temperatura ambiente. Para otimizar a produção e reduzir desperdícios, você decide usar Machine Learning para prever a demanda com base na temperatura.

### Objetivos
- Treinar um modelo de regressão para prever vendas de sorvete.
- Registrar e gerenciar o modelo usando o MLflow.
- Implementar o modelo para previsões em tempo real no Azure.
- Criar um pipeline estruturado para treinamento e teste do modelo.

## Implementação no Azure

### Configuração do Ambiente
1. **Azure Machine Learning (AML)**: Crie um workspace no AML para centralizar todos os recursos do projeto.
2. **Experimentos**: Utilize o AML para criar experimentos e treinar modelos de regressão com bibliotecas como Scikit-learn.
3. **MLflow**: Integre o MLflow para rastrear métricas, parâmetros e artefatos do modelo.

### Treinamento e Implantação do Modelo
- **Treinamento**: Treine o modelo utilizando dados históricos de vendas e temperatura.
- **Implantação**: Crie endpoints de inferência no AML para previsões em tempo real, utilizando Azure Kubernetes Service (AKS) ou Azure Container Instances (ACI).

### Pipeline e Monitoramento
- **Pipeline de Machine Learning**: Automatize o fluxo de trabalho desde o pré-processamento até a implantação.
- **Monitoramento**: Utilize ferramentas do AML para monitorar o desempenho do modelo em produção, como detecção de desvio de dados.

## Imagens do Projeto

### Pipeline de Machine Learning
![Pipeline de Machine Learning](DIO_modelo.png)

### Resultados do Modelo
![Resultados do Modelo](score_data.png)

### Jobs de Automated ML
![Jobs de Automated ML](Screenshot_From_2025-03-11_02-28-12.png)

## Conclusão
Este projeto demonstra como utilizar o Azure Machine Learning para criar um modelo preditivo que ajuda a otimizar a produção de sorvete com base na temperatura. A implementação no Azure garante escalabilidade, reprodutibilidade e monitoramento contínuo do modelo.

Para mais detalhes, visite o [repositório do projeto no GitHub](https://github.com/rquaresma42/dio_project_rhq).