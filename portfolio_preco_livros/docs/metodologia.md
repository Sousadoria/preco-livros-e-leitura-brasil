# Metodologia e dicionário dos dados

## Unidade de análise

Brasil. Período principal 2010–2024 para preço editorial; dados de varejo disponíveis de 2015–2024 (com lacunas e diferenças de cobertura); dados de leitura da série Retratos da Leitura.

## Indicadores

- **Preço médio editorial:** faturamento de vendas ao mercado dividido por exemplares, por subsetor. Para comparação de longo prazo, usamos Obras Gerais em 2010 e 2024. Não equivale ao preço final pago pelo consumidor.
- **Preço médio no varejo:** valor médio de livros vendidos no conjunto de livrarias, comércio eletrônico e varejistas colaboradores monitorados pelo Nielsen BookScan. Não há decomposição pública homogênea por canal.
- **Preço real:** preço nominal deflacionado pelo IPCA. Entre 2010 e 2024, aplicamos o fator acumulado composto dos IPCA anuais de 2011 a 2024 (aprox. 2,2221). Entre 2021 e 2024 no varejo, aplicamos os índices de 2022, 2023 e 2024 (aprox. 1,1602).
- **Acessibilidade:** preço médio varejista dividido pelo salário mínimo nominal do ano. É um indicador ilustrativo, não uma medida de renda disponível ou desigualdade.
- **Leitores:** Retratos da Leitura considera leitor quem leu inteiro ou em parte ao menos um livro impresso ou digital nos três meses anteriores à entrevista.

## Cálculos centrais

- Varejo nominal 2021–2024: `50,66 / 41,28 - 1 = 22,72%`.
- Varejo real aproximado: `(50,66 / 41,28) / (1,0579 × 1,0462 × 1,0483) - 1 = 5,77%`.
- Preço editorial Obras Gerais nominal 2010–2024: `20,17 / 10,07 - 1 = 100,30%`.
- Preço editorial real aproximado: `(20,17 / 10,07) / 2,2221 - 1 = -9,86%`.
- Leitores estimados 2019–2024: `93,4 - 100,1 = -6,7 milhões` (aprox. -6,7%).

## Ressalvas

1. O preço médio muda quando muda a composição dos títulos, gêneros, edições, canais e descontos vendidos; não acompanha o mesmo livro ao longo do tempo.
2. O painel de varejo e a pesquisa editorial têm universos diferentes e não devem ser fundidos numa única série.
3. As edições dos relatórios podem atualizar a base e os fechamentos anuais; percentuais de releases podem diferir ligeiramente dos cálculos entre valores arredondados publicados.
4. A pesquisa de leitura traz diferenças de percentuais de 2019 entre a tabela histórica de 2024 e alguns materiais de divulgação. A base usa a tabela comparativa da edição de 2024: 52% em 2019 e 47% em 2024.
5. Alfabetização não é sinônimo de leitura de livros; não existe, neste projeto, uma série global comparável de número de leitores.
6. Correlação temporal não demonstra causalidade.
