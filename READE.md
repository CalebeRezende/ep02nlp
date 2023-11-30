# EP02: Projeto de Regressão e Quantização de Transformadores

## Visão geral
Este projeto envolve uma exploração detalhada do refinamento de codificadores na arquitetura Transformers, focando especificamente em modelos do tipo BERT. O objetivo principal é avaliar o desempenho destes modelos em tarefas de regressão numérica e explorar soluções para melhorar o seu desempenho em tais cenários. O projeto utiliza o corpus de revisão B2W, com foco na coluna 'texto de revisão', e envolve tarefas relacionadas à regressão e quantização de densidade vocálica.

# Uso
Para usar este notebook, navegue até o diretório que contém `EP02_main.ipynb` e execute:
```
caderno jupyter EP02_main.ipynb
```
Siga as instruções do notebook para executar as células.

## Conteúdo do caderno
O notebook `EP02_main.ipynb` contém vários componentes principais:
- **Configuração de GPU e RAM**: verifica a disponibilidade da GPU e o tamanho da RAM para garantir computação de alto desempenho.
- **Drive Mounting**: Código para montar o Google Drive para acessar arquivos de dados.
- **Pré-processamento**: Scripts para pré-processamento dos dados, incluindo tratamento do corpus de revisão da B2W.
- **Modelos de linha de base**: Estabelecimento de modelos de linha de base para comparação em tarefas de regressão.
- **Modelos de Regressão de Treinamento**: Treinamento de modelos BERT para regressão de densidade vocálica.
- **Testando Modelos de Regressão**: Avaliação dos modelos de regressão treinados.
- **Treinamento e teste de modelos de classificação**: Implementação de tarefas de quantização para densidade vocálica usando modelos de classificação.
