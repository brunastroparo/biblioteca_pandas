# biblioteca_pandas

# O conjunto de dados de varejo que temos disponível contém informações sobre as vendas de uma loja virtual com atuação em todo o Brasil, comercializando produtos de diversos departamentos. Além disso, a loja utiliza diferentes canais de venda, como marketplaces e sua própria plataforma, entre outros.

Premissas de negócio: Ao realizar a análise dos dados, é essencial levar em consideração algumas premissas de negócio. A primeira delas é que, devido a um erro no sistema, algumas transações não possuem registro do estado (UF). Para lidar com essa questão, decidiu-se que essas vendas serão tratadas como se fossem do estado de Mato Grosso do Sul (MS). A segunda premissa é que o preço final de um produto nunca deve ser maior que o valor incluindo o frete.

Métricas:
Com base nesse contexto e nas premissas de negócio definidas, podemos analisar as seguintes métricas:

1.Departamentos mais vendidos: A partir dos dados de vendas, podemos identificar os departamentos mais populares entre os clientes. Essa informação é útil para compreender quais produtos são mais procurados, permitindo ajustar a estratégia de vendas da loja de forma alinhada às preferências dos consumidores.

2.Média de preço com frete por departamento: Para entender o comportamento de preços em cada departamento, podemos calcular a média de preço com frete por nome de departamento. Essa métrica auxilia na identificação dos departamentos mais rentáveis, ajudando a ajustar a precificação dos produtos conforme a margem de lucro desejada.

3.Quantidade de vendas por mês: Analisando o volume de vendas em cada mês, é possível detectar padrões sazonais no comportamento de compra dos clientes, permitindo o planejamento de campanhas de marketing específicas para cada período.

4.Média de renda por canal de venda: Ao identificar a média de renda dos clientes em cada canal de venda, a loja pode adaptar suas estratégias de marketing e vendas para cada perfil de público, visando uma abordagem mais segmentada.

5.Média de idade dos clientes por bandeira: Compreender a faixa etária dos clientes por bandeira ajuda a identificar perfis de consumidores, permitindo ajustes na estratégia de vendas para melhor atender as necessidades de cada público-alvo.
