# 📊 Análise de Desempenho de Lojas - Projeto Data Science

Este projeto tem como objetivo analisar o desempenho de quatro lojas a partir de dados reais de vendas, avaliações de clientes e logística, com a finalidade de apoiar uma decisão de negócio: **qual loja deve ser vendida pelo proprietário**.

## 🧠 Objetivo

Auxiliar o Sr. João, proprietário das lojas, a identificar a unidade com pior desempenho com base em:

- Faturamento total
- Categorias de produtos mais e menos vendidas
- Média de avaliações dos clientes
- Produtos mais e menos vendidos
- Frete médio por loja

## 🗂️ Fontes de Dados

Os dados foram coletados de arquivos CSV públicos hospedados no repositório da [Alura](https://github.com/alura-es-cursos):

- `loja_1.csv`
- `loja_2.csv`
- `loja_3.csv`
- `loja_4.csv`

## 📈 Ferramentas Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Folium (para mapas e heatmaps)
- Google Colab

## 🧾 Relatório Final

Após a análise completa, concluiu-se que a **Loja 4** apresenta o pior desempenho geral:

- Menor faturamento total
- Uma das piores médias de avaliação, apesar de vendas semelhantes à Loja 1
- Predomínio de categorias como brinquedos e móveis, que podem impactar a satisfação do cliente
- Frete médio mais barato, mas não suficiente para compensar os demais indicadores

Com base nesses dados, recomenda-se a **venda da Loja 4**.

## 📎 Resultados Visuais

O projeto inclui:

- Gráficos de barras e gráficos empilhados por categoria
- Análise percentual por categoria
- Heatmap de localização de vendas
- Cálculos estatísticos e médias por loja

## 🚀 Como Rodar

Você pode acessar o projeto diretamente no Google Colab ou clonar este repositório para executar localmente com Jupyter Notebook:

```bash
git clone https://github.com/ThPontes/Challenge-AluraStore.git
cd Challenge-AluraStore
