# Desafio: Dados que Transformam

**Nome:** Seu Nome  
**E-mail:** seu@email.com  
**LinkedIn (opcional):** https://linkedin.com/in/seu-perfil

## Repositório

A versão completa com código  está disponível em:

link do colab


## 1. Introdução

A partir desse conjunto de dados, este trabalho se propõe a enxergar além dos números e revelar padrões que em um cenário real ajudariam na tomada de desição.

O desafio proposto foi dividido em etapas que envolvem desde a organização e preparação dos dados até a seleção de perguntas-chave voltadas para diferentes áreas do e-commerce, como vendas, logística, satisfação do cliente, finanças e marketing. Cada escolha analítica buscou destacar um aspecto relevante do negócio a partir da leitura cuidadosa dos dados disponíveis.

---

## 2. Análises e Resultados

Abaixo, cada análise está estruturada com a questão escolhida, a visualização correspondente (imagem) e a interpretação dos dados. Cada seção representa um dos eixos analíticos propostos pelo desafio.

---

### 2.1 Análise de Performance de Vendas

**Questão escolhida:** B) Análise de Sazonalidade: Investigar padrões de sazonalidade nas vendas, identificando os períodos do ano com maior volume de vendas.

**Visualização:**

![Gráfico: Volume por Categoria](caminho/para/imagem1.png)

**Interpretação:**

## Análise dos Meses de Maior Desempenho (2016-2018)

Este estudo explora os picos de faturamento e volume de vendas, identificando padrões de sazonalidade ao longo dos anos.

| Ano | Métrica              | Melhor Mês | Valor/Unidades |
| :-- | :------------------- | :--------- | :------------- |
| 2016| Faturamento          | Outubro    | R$ 67.941,17   |
| 2016| Unidades Vendidas    | Outubro    | 362 unidades   |
| 2017| Faturamento          | Novembro   | R$ 1.550.848,82|
| 2017| Unidades Vendidas    | Novembro   | 8.811 unidades |
| 2018| Faturamento          | Maio       | R$ 1.531.971,40|
| 2018| Unidades Vendidas    | Março      | 8.614 unidades |

---

### Insights da Análise:

* **2016:** Os dados de 2016 apontam Outubro como o mês de desempenho superior, com os maiores valores observados tanto em faturamento quanto em unidades vendidas. Há uma correlação direta entre volume e receita neste período.
* **2017:** Em 2017, registrou-se um crescimento substancial, com Novembro apresentando o pico em ambas as métricas – faturamento e volume de vendas. Este ano representa um ponto de inflexão significativo na performance geral.
* **2018:** O ano de 2018 exibe uma particularidade: o maior volume de unidades vendidas ocorreu em Março, enquanto o pico de faturamento foi atingido em Maio. Essa divergência pode indicar transações com maior valor unitário em Maio ou dinâmicas distintas de mercado e precificação entre os meses.

---

### 2.2 Análise de Logística

**Questão escolhida:** B) Desempenho de Transportadoras: Avaliar o desempenho de diferentes transportadoras com base no tempo de entrega e na satisfação do cliente.

**Visualização:**

![Gráfico: Prazo de Entrega](caminho/para/imagem2.png)

**Interpretação:**

## Análise dos Meses de Maior Desempenho (2016-2018)

Este estudo explora os picos de faturamento e volume de vendas, identificando padrões de sazonalidade ao longo dos anos.

| Ano | Métrica              | Melhor Mês | Valor/Unidades |
| :-- | :------------------- | :--------- | :------------- |
| 2016| Faturamento          | Outubro    | R$ 67.941,17   |
| 2016| Unidades Vendidas    | Outubro    | 362 unidades   |
| 2017| Faturamento          | Novembro   | R$ 1.550.848,82|
| 2017| Unidades Vendidas    | Novembro   | 8.811 unidades |
| 2018| Faturamento          | Maio       | R$ 1.531.971,40|
| 2018| Unidades Vendidas    | Março      | 8.614 unidades |

---

### Insights da Análise:

* **2016:** Os dados de 2016 apontam Outubro como o mês de desempenho superior, com os maiores valores observados tanto em faturamento quanto em unidades vendidas. Há uma correlação direta entre volume e receita neste período.
* **2017:** Em 2017, registrou-se um crescimento substancial, com Novembro apresentando o pico em ambas as métricas – faturamento e volume de vendas. Este ano representa um ponto de inflexão significativo na performance geral.
* **2018:** O ano de 2018 exibe uma particularidade: o maior volume de unidades vendidas ocorreu em Março, enquanto o pico de faturamento foi atingido em Maio. Essa divergência pode indicar transações com maior valor unitário em Maio ou dinâmicas distintas de mercado e precificação entre os meses.

**Conclusão da Análise:** A partir da análise dos dados, é possível identificar padrões anuais de sazonalidade e a evolução notável no faturamento de 2016 para 2017 e 2018. A discrepância observada em 2018, onde o maior volume não correspondeu ao maior faturamento, sublinha a importância de uma análise multifacetada para uma compreensão abrangente do desempenho.

---

### 2.3 Análise de Satisfação do Cliente

**Questão escolhida:** A) Avaliações de Produtos: Analisar a distribuição das avaliações dos produtos e identificar os produtos com as melhores e piores avaliações.

**Visualização:**

![Gráfico: Satisfação x Atraso](caminho/para/imagem3.png)

## Análise de Avaliações de Produtos: Distribuição e Desempenho por Categoria

O objetivo desta análise foi investigar a distribuição das notas de avaliação dos clientes e identificar categorias de produtos com os melhores e piores desempenhos médios.

A análise da distribuição geral das notas (`review_score`) indica como maioria as avaliações positivas (notas 4 e 5), sugerindo uma percepção geral favorável dos produtos. A ocorrência de notas 1 e 2 em volume notável aponta para áreas potenciais de insatisfação. A média geral das avaliações serve como um parâmetro inicial da satisfação do cliente.

### Desempenho por Categoria de Produto

Para identificar o desempenho por categoria, calculamos a média das avaliações por `product_category_name`, considerando apenas categorias com um volume representativo de avaliações (e.g., mais de 100).

---

### 2.4 Financeiro

**Questão escolhida:** (exemplo: "Lucratividade por Categoria")

**Visualização:**

![Gráfico: Lucratividade por Categoria](caminho/para/imagem4.png)

**Interpretação:**

Compare categorias mais e menos lucrativas. Avalie se alto volume de vendas implica maior lucro. Fale sobre margens, equilíbrio entre custo e receita, e categorias deficitárias.

---

### 2.5 Marketing

**Questão escolhida:** (exemplo: "Conversão de Vendas por Fonte de Tráfego")

**Visualização:**

![Gráfico: Conversão por Fonte](caminho/para/imagem5.png)

**Interpretação:**

Avalie quais canais convertem melhor. Existe desperdício de orçamento em canais pouco eficientes? Há oportunidades de otimização de campanhas?

---

## 3. Considerações Finais

Apresente as conclusões gerais do trabalho. Aponte os principais insights obtidos a partir das análises, como oportunidades de negócio, gargalos operacionais ou estratégias eficazes. Comente sobre a importância da análise exploratória para o apoio à decisão.
