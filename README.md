# Desafio-7-DNC---
Modelo de Clusterização com RFM de um ecommerce. O mesmo foi feito utilizado a metodologida do CRISP - DM.

# Desafio: Crie um Modelo de Análise das Métricas RFV

Introdução
Este repositório contém um desafio de clustering para criar um sistema de agrupamento de perfis de clientes para um e-commerce. O objetivo é analisar o modelo mais eficiente, capaz de tornar as análises mais simplificadas para a empresa.

# Contexto
Você foi contratado por uma empresa de e-commerce que busca entender melhor o comportamento de seus clientes para personalizar as campanhas de marketing. A empresa disponibilizou uma base de dados contendo informações sobre clientes, produtos e transações realizadas entre os anos de 2010 e 2011.

Com base nesses dados, você precisa agrupar os clientes em clusters conforme seu comportamento de compra, permitindo identificar padrões e características em comum, como:

Clientes que compram os mesmos produtos;

Clientes que possuem a mesma frequência de compras;

Clientes que gastam mais dinheiro em suas compras.

A partir desses clusters, gere insights para que a empresa possa segmentar melhor sua base de clientes e personalizar suas campanhas de marketing.

# Base de Dados
Os dados fornecidos possuem informações de transações de compras de uma loja de e-commerce em 38 países e territórios, com mais de 4.000 clientes únicos e mais de 540.000 transações.

# Estrutura dos Dados
InvoiceNo: Identificação da transação

StockCode: Código de estoque do produto

Description: Descrição do produto

Quantity: Quantidade de produtos por transação

InvoiceDate: Data da transação

UnitPrice: Preço unitário do produto

CustomerID: Identificação do cliente

Country: País de origem da transação

# Etapas do Desafio
1. **Análise Exploratória dos Dados**
Carregando a base de dados.

Realizando uma descrição estatística dos dados.

Visualizando as distribuições e identifique a relevância das colunas para a análise.

Verificando a presença de dados nulos, duplicados, outliers e inconsistências.

2. **Pré-processamento dos Dados**
Realizando a normalização dos dados.

Selecionando as variáveis mais relevantes para o modelo.

Removendo os dados nulos, duplicados, outliers e inconsistentes.

3. **Seleção do Algoritmo de Clusterização**
Escolhendo um algoritmo adequado para a base de dados, como K-Means, DBSCAN, Hierárquico ou Mean Shift.

Encontrando a quantidade ideal de clusters através dos métodos de Elbow ou Silhouette Score.

Implementando o algoritmo escolhido.

4. **Análise dos Clusters Obtidos**
Identificando s padrões e características em comum entre os clientes.

Plotando gráficos para auxiliar na análise.

5. **Interpretação dos Resultados Obtidos**
Descrevendo o perfil de compras dos clientes de cada cluster.

Justificando como essa análise pode ser útil para a empresa na segmentação de seus clientes e personalização das campanhas de marketing.

Sugirindo ações possíveis com base nas análises realizadas.
