## E-commerce-Growth-CRM-Analytics
Análise de funil de marketing e perfil de clientes para um e-commerce, com dados de campanhas de CRM (7.000 envios) e base de pedidos.

1. Diagnóstico do funil de marketing
Base: 7.000 mensagens enviadas

Etapa	Volume	Taxa sobre envios
Aberturas	1.960	28,0%
Cliques	448	6,4%
Conversões	58	0,83%
Taxa de conversão após o clique: 12,95% (58 / 448) Taxa de clique sobre aberturas: 22,9% (448 / 1.960)


O que os resultados indicam
Abertura (28%): existe espaço para melhorar assuntos e segmentação das campanhas.
Clique (6,4%): aproximadamente 22,9% das mensagens abertas geraram cliques.
Conversão após clique (12,95%): cerca de 87% dos cliques não resultaram em conversão.
Variáveis que poderiam explicar a queda no funil, mas não estão no dataset: página de destino, preço, frete, checkout, disponibilidade de produtos e experiência de compra.


2. Ticket médio e distribuição por faixa de receita
Métrica	Valor	Fórmula
Ticket médio geral	R$ 340,95	receita total ÷ quantidade de produtos
Média do ticket médio	R$ 483,50	média dos tickets médios
Faixa R$ 950–1000	R$ 494,50	média do ticket médio na faixa
Faixa R$ 50–100	R$ 454,60	média do ticket médio na faixa
A faixa R$ 950–1000 fica R$ 11,00 (+2,3%) acima da média geral de R$ 483,50.
A faixa R$ 50–100 tem ticket médio de R$ 454,60, abaixo da média geral — é a faixa de alto volume e ticket menor.
Nota metodológica: o ticket médio geral (razão entre receita total e quantidade de produtos) e a média dos tickets médios por faixa são métricas distintas. A primeira pondera pelo volume de cada faixa; a segunda atribui peso igual a cada faixa. Por isso os valores não devem ser comparados diretamente.


3. Perfil dos clientes
Clientes de 25 a 34 anos com gasto entre R$ 50 e 100 representam 6,93% do total de pedidos.
A faixa de receita R$ 50–100 concentra o maior volume de pedidos, com ticket médio abaixo da média geral.
Pelo boxplot dos principais influenciadores, quem consome mais está na faixa etária de 25 a 34 anos — há forte preponderância desse perfil na base.


Insights acionáveis
O faturamento bruto apresentou crescimento exponencial. Foram R$ 184,7 mil em descontos no período; sem comparação com o ano anterior, não é possível medir o impacto anual desse valor.
Campanhas de e-mail para o perfil 25–34 anos, focadas em produtos na faixa de R$ 50–100: melhor performance em quantidade, mas com ticket médio menor. Vale testar ofertas de maior valor para elevar o ticket desse mesmo perfil.
Campanhas com melhor conversão: Welcome Series (12), VIP Early Access (18) e Winback 90d (14) — priorizar esses fluxos e replicar a lógica de segmentação deles nas demais campanhas.
CTR em queda: a variação acumulada do CTR ficou negativa (-0,03%). A performance acumulada frente aos meses anteriores é boa, mas o clique é o ponto a atacar.
Entrega: 93,2% do total de pedidos foram entregues, indicando boa eficácia operacional de vendas.


5. Metodologia e limitações
Dados de campanha cobrem 7.000 envios de CRM; o ticket médio e o perfil de clientes consideram a base completa de pedidos. São recortes diferentes e não devem ser comparados diretamente.
Não há dados de anos anteriores para os descontos (R$ 184,7 mil), o que impede a leitura de tendência.
Variáveis de conversão ausentes no dataset: página de destino, preço, frete, checkout, disponibilidade de produtos e experiência de compra.


6. Recomendações
Testar A/B de assunto e remetente para elevar a taxa de abertura acima de 28%.
Priorizar campanhas e segmentação dos fluxos Welcome Series, VIP Early Access e Winback 90d, que já convertem melhor.
Investir em campanhas de e-mail para o perfil 25–34 anos em produtos de R$ 50–100, equilibrando volume e ticket.
Acompanhar o CTR como métrica de alerta, já que a variação acumulada está negativa.
Instrumentar o pós-clique (destino, checkout, frete) para explicar os 87% de cliques que não convertem.

