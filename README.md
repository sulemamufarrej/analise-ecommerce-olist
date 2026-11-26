# Análise de E-Commerce e Desempenho de Vendas (Olist)

## Objetivo do Projeto
Integrar e analisar dados transacionais de comércio eletrónico da Olist para avaliar a evolução das vendas, o desempenho por categoria de produto e região, a eficiência dos prazos de entrega e o impacto da logística na satisfação dos clientes.

## Ferramentas e Bibliotecas
* **Linguagem:** Python
* **Manipulação e Análise de Dados:** Pandas, NumPy
* **Visualização de Dados:** Matplotlib, Seaborn, Plotly

## Estrutura dos Dados
O estudo baseia-se no conjunto de dados público de e-commerce da **Olist**:

* **Pedidos e pagamentos:** identificadores de encomenda (`order_id`), estado do pedido, carimbos temporais de compra, aprovação e entrega, além de métodos e valores de pagamento.
* **Itens, produtos e vendedores:** preços, custos de frete, categorias de produtos e localização geográfica de clientes e vendedores.
* **Avaliações:** pontuações de satisfação (`review_score`) atribuídas pelos clientes após a entrega.

## Metodologia
1. **Integração e Limpeza de Dados:** Cruzamento (`merge`) de múltiplas tabelas relacionais, tratamento de valores ausentes, conversão de datas e criação de métricas derivadas (tempo de entrega, atraso face ao prazo estimado e ticket médio).
2. **Análise Exploratória e Comercial (EDA):** Avaliação da evolução temporal de pedidos e receita, concentração por categorias e estados, e distribuição dos meios de pagamento.
3. **Análise Logística e Satisfação:** Cruzamento entre prazos de entrega, atrasos logísticos e notas de avaliação dos clientes para identificar os principais fatores de insatisfação.

## Principais Conclusões e Recomendações
* Identificação das categorias e regiões com maior volume de vendas e receita, bem como da forte correlação entre atrasos na entrega e avaliações negativas (`review_score` baixo).
* Recomendações práticas para otimização de prazos estimados, acompanhamento de rotas críticas e melhoria da experiência pós-compra.
