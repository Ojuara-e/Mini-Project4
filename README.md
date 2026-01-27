# Fundamentos de Linguagem Python - Do Básico a Aplicações de IA
## Mini-Projeto 4 (Limpeza, Engenharia de Atributos e Análise Exploratória de Dados de Vendas com Pandas)

### 1.1. Contexto 

Uma empresa de e-commerce, em plena fase de crescimento, coleta diariamente um volume significativo de dados transacionais de suas vendas online. Esses dados, provenientes de diversas fontes, são armazenados em um sistema bruto e incluem informações sobre pedidos, clientes, produtos, categorias e status de entrega.

Atualmente, a gestão da empresa enfrenta dificuldades para tomar decisões estratégicas baseadas em dados, pois os relatórios gerados a partir desse sistema bruto são inconsistentes e pouco confiáveis. Tentativas de analisar o desempenho de produtos ou entender o comportamento do consumidor resultaram em conclusões contraditórias, gerando incerteza nas áreas de marketing, estoque e planejamento financeiro.

### 1.2. Problema de Negócio 

A empresa não consegue extrair inteligência de negócio de seus dados de vendas devido à baixa qualidade e à falta de estruturação das informações. Os dados brutos contêm problemas recorrentes, como:

- Dados Faltantes: Pedidos sem registro de quantidade ou status, impedindo um cálculo preciso do faturamento e da eficiência logística.

- Inconsistências e Erros: Formatos de dados incorretos (ex: preços como texto) e erros de digitação que corrompem as análises.

- Informações Duplicadas: Registros de vendas que aparecem mais de uma vez, inflando artificialmente os números de receita e unidades vendidas.

- Valores Discrepantes (Outliers): Dados anômalos que distorcem as médias e as análises estatísticas, levando a uma compreensão equivocada do comportamento padrão de compra.
<!-- Trabalho Desenvolvido no Curso da Data Science Academy - www.datascienceacademy.com.br -->

Essa falta de dados confiáveis impede a empresa de responder a perguntas críticas de negócio, tais como:

- Quais são nossos produtos e categorias mais lucrativos?

- Qual é a nossa tendência de vendas ao longo do tempo?

- Como está a eficiência de nossa operação logística (percentual de entregas, pendências, etc.)?

A incapacidade de responder a essas perguntas resulta em alocação ineficiente de recursos, perda de oportunidades de vendas e dificuldade em planejar o futuro do negócio de forma estratégica.

### 1.3. Objetivos do Projeto 

O objetivo principal deste projeto é transformar os dados brutos de vendas em um ativo confiável e acionável, permitindo que a empresa baseie suas decisões estratégicas em informações precisas.

Para alcançar este objetivo, os seguintes passos serão executados:

- Limpeza e Validação: Implementar um processo para identificar e corrigir as inconsistências nos dados, tratando valores ausentes, removendo duplicatas, corrigindo tipos de dados e lidando com outliers.

- Análise Exploratória de Dados (EDA): Analisar o conjunto de dados limpo para extrair insights iniciais e responder às perguntas de negócio fundamentais.

- Geração de Insights Visuais: Criar um conjunto de visualizações que comuniquem de forma clara e objetiva os principais indicadores de desempenho de vendas.

### 1.4. Critérios de Sucesso 

O projeto será considerado um sucesso quando formos capazes de entregar:

- Um conjunto de dados (dataset) limpo e validado, pronto para ser utilizado em análises futuras.

- Um relatório de análise respondendo com clareza às seguintes questões:

    - O faturamento total e a receita por categoria de produto.

    - A identificação do top 5 produtos mais vendidos em quantidade e em receita.

    - Um gráfico mostrando a tendência de vendas diárias no período analisado.

    - Uma análise da distribuição percentual dos status de entrega (Entregue, Pendente, Cancelado).

O sucesso final será medido pela capacidade da equipe de gestão de utilizar os insights gerados para tomar, com confiança, pelo menos uma decisão de negócio informada (ex: ajustar o estoque do produto mais vendido ou criar uma campanha de marketing para a categoria mais lucrativa).
