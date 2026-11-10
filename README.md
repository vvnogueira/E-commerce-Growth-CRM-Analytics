## E-commerce-Growth-CRM-Analytics
### Contexto empresarial


**Vitta Commerce**


E-commerce brasileiro de produtos para casa, decoração e lifestyle.
A empresa cresceu rapidamente nos últimos 12 meses, aumentando seus investimentos em aquisição de clientes.
Entretanto, a diretoria percebeu alguns problemas:
•	O investimento em marketing está aumentando.
•	O número de clientes novos cresce, mas a recompra não acompanha.
•	O CAC parece estar aumentando.
•	Algumas campanhas geram muitas vendas, mas pouca receita líquida.
•	A equipe de CRM não sabe quais clientes priorizar.
•	Não existe uma estratégia clara de retenção baseada em dados.

Objetivo principal:
Identificar oportunidades para aumentar a receita e a rentabilidade da empresa, melhorando a aquisição, conversão, retenção e reativação de clientes por meio de decisões data-driven

2. Essas perguntas serão o núcleo do projeto. Cada análise deve responder a uma pergunta empresarial específica.
A. Marketing Performance
•	Qual canal de marketing gera mais receita?
•	Qual canal apresenta melhor eficiência de aquisição?
•	Quais campanhas apresentam maior CAC?
•	O canal com maior número de clientes é realmente o mais rentável?
•	Existe diferença entre receita atribuída e receita total?
•	Quais campanhas devem receber mais ou menos orçamento?
B. Customer Acquisition
•	Como evoluiu a aquisição de novos clientes?
•	O CAC está aumentando ao longo do tempo?
•	Quais segmentos possuem maior custo de aquisição?
•	Qual canal atrai clientes com maior potencial de recompra?
•	Existe sazonalidade na aquisição?
C. Customer Retention
•	Qual percentual dos clientes retorna para comprar?
•	Em quanto tempo ocorre a segunda compra?
•	Quais canais atraem clientes mais recorrentes?
•	Quais segmentos apresentam maior churn comportamental?
•	Quais cohorts apresentam melhor retenção?
D. CRM & Customer Segmentation
•	Quais clientes devem receber campanhas de reativação?
•	Quais clientes apresentam maior valor potencial?
•	Quais clientes estão próximos de abandonar a empresa?
•	Quais segmentos respondem melhor a descontos?
•	Como construir uma estratégia de comunicação personalizada?
E. Business Strategy
•	Onde a empresa deveria aumentar o investimento?
•	Qual é a oportunidade financeira de melhorar a recompra?
•	Qual seria o impacto de reduzir o CAC?
•	Qual estratégia de CRM deveria ser priorizada?
•	Como medir se as campanhas realmente funcionaram?


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
O faturamento bruto cresceu de forma exponencial ao longo do ano com o CTR praticamente estável, indicando ganho de escala sem perda de engajamento por mensagem. Foram R$ 184,7 mil em descontos no período; sem comparação com o ano anterior, não é possível medir o impacto anual desse valor.
Campanhas de e-mail para o perfil 25–34 anos, focadas em produtos na faixa de R$ 50–100: melhor performance em quantidade, mas com ticket médio menor. Vale testar ofertas de maior valor para elevar o ticket desse mesmo perfil.
Campanhas com melhor conversão: Welcome Series (12), VIP Early Access (18) e Winback 90d (14) — priorizar esses fluxos e replicar a lógica de segmentação deles nas demais campanhas.
CTR estável no acumulado: a variação do CTR no ano ficou em -0,03 p.p., com o indicador oscilando entre 1,94% (março) e 15,79% (janeiro) e fechando o ano em 6,42%. O ponto de atenção não é a tendência — é o nível.
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

