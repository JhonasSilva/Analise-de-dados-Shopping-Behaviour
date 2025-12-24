## Análise de Vendas — Projeto de Data Analytics

Este projeto tem como objetivo realizar uma análise estatística descritiva e comparativa sobre um conjunto de dados de vendas no varejo, utilizando Python e bibliotecas de análise de dados.
A análise busca compreender padrões de faturamento, comportamento dos clientes, sazonalidade e desempenho das categorias, gerando insights acionáveis para tomada de decisão de negócio.

---

## Objetivos do Projeto:

Explorar o comportamento das vendas por categoria, gênero e estação do ano
Identificar segmentos com melhor e pior desempenho
Avaliar o impacto de fatores como assinatura, frequência de compra e satisfação do cliente
Apoiar decisões estratégicas relacionadas a marketing, estoque e experiência do cliente

---

## Estrutura do Projeto:
```text
├── data/
│   ├── dataset_tratado.csv
│   └── shopping_behavior_updated.csv
│
├── images/
│   ├── categoria_avaliacao.png
│   ├── grafico_categoria.png
│   ├── grafico_estacao.png
│   ├── grafico_genero.png
│   ├── media_faturamento_assinantes.png
│   ├── media_categoria_estacao.png
│   └── media_frequencia.png
│
├── notebooks/
│   ├── 01_exploracao_dados.ipynb
│   ├── 02_limpeza_tratamento.ipynb
│   ├── 03_analise_descritiva.ipynb
│   └── 04_analise_comparativa.ipynb
│
└── README.md
```
---

## Tecnologias Utilizadas

- Python
- Pandas – manipulação e agregação de dados
- Matplotlib – visualização de dados
- Jupyter Notebook

---

## Etapas da Análise
# Estatística Descritiva:

Nesta etapa, foram analisados os principais indicadores gerais do negócio, com foco em entender o cenário atual.

# Principais análises realizadas:

- Faturamento total
- Ticket médio
- Faturamento por categoria
- Distribuição de compras por gêner
- Ticket médio por gênero
- Faturamento por estação do ano
- Avaliação média dos produtos

# Principais resultados:

- Faturamento total: USD 233.081
- Ticket médio: USD 59,76
- Categoria com maior faturamento: Clothing
- Estação com maior faturamento: Outono (Fall)
- Avaliação média geral: 3,7

---

## Estatística Comparativa:

A análise comparativa teve como objetivo identificar diferenças de desempenho entre grupos, aprofundando os insights obtidos na etapa descritiva.

# Perguntas de negócio analisadas:

- Existe diferença no ticket médio entre categorias e estações do ano?
- Clientes assinantes gastam mais do que não assinantes?
- O ticket médio varia de acordo com a frequência de compra?
- Há diferenças relevantes na avaliação média entre categorias?

# Principais Insights Extraídos:

- Outono (Fall) se consolida como o período mais estratégico, apresentando o maior faturamento e os maiores tickets médios, especialmente nas categorias Footwear, Clothing e Accessories.
- A assinatura não apresenta impacto significativo no ticket médio, indicando oportunidade de revisão dos benefícios oferecidos.
- Clientes com menor frequência de compra tendem a apresentar ticket médio ligeiramente superior, enquanto clientes mais frequentes realizam compras de menor valor unitário.
- A categoria Clothing, apesar de sua forte participação no faturamento, apresenta a menor avaliação média, indicando possível gap entre volume de vendas e satisfação do cliente.
- Footwear se destaca positivamente na avaliação média, sugerindo boa percepção de qualidade pelos clientes.

---

## Conclusão:

A partir das análises descritiva e comparativa, foi possível identificar padrões relevantes de desempenho e comportamento dos clientes. O estudo evidencia a importância da sazonalidade, especialmente do outono, como período estratégico para ações comerciais.
Além disso, os resultados indicam oportunidades claras de melhoria no programa de assinatura e na experiência do cliente em determinadas categorias, fornecendo uma base sólida para decisões estratégicas futuras.

---

## Contato:
- Linkedin: www.linkedin.com/in/jhonas-silvac
- Email: jhonassilvac@gmail.com
