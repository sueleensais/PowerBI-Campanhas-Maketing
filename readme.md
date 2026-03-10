# Análise de Desempenho de Campanhas de Marketing

## Descrição
Este projeto consiste no desenvolvimento de uma solução de Business Intelligence voltada para a área de Marketing. O objetivo central é a transformação de dados brutos sobre perfis de consumidores e interações publicitárias em um ecossistema de dashboards interativos, permitindo a extração de insights estratégicos sobre comportamento de consumo e eficácia de conversão.

A solução abrange todo o fluxo de dados, desde o processo de ETL (Extração, Transformação e Carga) até a aplicação de técnicas de Storytelling para suporte à decisão gerencial.

## Pipeline
1. Coleta e Extração 
2. Tratamento e Transformação 
3. Modelagem de Dados 
4. Processamento de Métricas 
5. Visualização e Storytelling 

## Objetivos Técnicos
* Modelagem de Dados: Estruturação de relacionamentos entre tabelas para garantia de integridade e performance analítica.
* DAX Avançado: Desenvolvimento de medidas personalizadas para cálculo de KPIs de performance e comportamento de compra.
* Tratamento de Dados: Limpeza, padronização e identificação de outliers via Power Query.
* Análise Visual: Construção de dashboards com foco em usabilidade e clareza na apresentação de métricas complexas.

## Tecnologias e Ferramentas
* Power BI Desktop: Construção dos relatórios e dashboards.
* Power Query: Motor de transformação e higienização de dados.
* Linguagem DAX: Cálculos estatísticos e indicadores de negócio.
* Modelagem de Dados: Organização eficiente dos dados para análise multidimensional.

## Estrutura dos Dashboards
O relatório está estruturado em quatro perspectivas complementares:

1. Visão do Cliente: Análise do perfil demográfico, incluindo escolaridade, estado civil e canais de preferência.
2. Comportamento de Compra: Estudo da correlação entre nível de renda, composição familiar e volume de gastos.
3. Performance das Campanhas: Monitoramento das taxas de conversão e adesão às ofertas de marketing.
4. Padrões de Compra (PDV): Análise temporal e espacial de vendas segmentadas por país.

## Principais Insights Extraídos
* Perfil de Conversão: Clientes com ensino superior e maior nível de renda apresentam a melhor resposta a campanhas de marketing direto.
* Canais de Venda: Identificou-se que lojas físicas detêm a maior preferência de compra, frequentemente impulsionadas pelo uso estratégico de cupons de desconto.
* Composição Familiar: O ticket médio de perfis solteiros é superior ao de famílias com filhos ou adolescentes, indicando oportunidades distintas de segmentação.
* Impacto Temporal: A análise revelou uma retração no volume de compras em 2021, permitindo correlacionar o impacto de fatores externos no consumo global.

## Demonstração das Visualizações

| Visão do Cliente | Comportamento de Compra |
| :---: | :---: |
| ![Cliente](Imagens/Cliente.png) | ![Comportamento](Imagens/Comportamento.png) |

| Performance de Campanha | Ponto de Venda (Global) |
| :---: | :---: |
| ![Campanha](Imagens/Campanha.png) | ![PontoDeVenda](Imagens/PontoDeVenda.png) |

---
*Projeto desenvolvido como parte do programa de formação em Business Intelligence da Data Science Academy.*


