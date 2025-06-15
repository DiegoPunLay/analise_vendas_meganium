
# Análise Estratégica de Vendas da Meganium - Consoles Retrô

## Visão Geral do Projeto

Este repositório contém uma análise estratégica abrangente dos dados de vendas da **Meganium**, uma empresa especializada na venda de consoles de videogame retrô. A análise visa identificar tendências, otimizar estratégias de vendas, precificação, descontos, logística e marketing para impulsionar o faturamento e a rentabilidade da empresa.

Os dados de vendas foram coletados de três plataformas principais: **AliExpress, Etsy e Shopee**, abrangendo o período de Maio a Outubro de 2024. As análises financeiras foram padronizadas para Dólar Americano (USD) utilizando taxas de câmbio históricas para garantir precisão comparativa.

## Sobre a Empresa Meganium (Fictícia)

A Meganium é uma empresa apaixonada pelo universo dos jogos retrô, dedicada a trazer de volta a nostalgia e a diversão dos consoles clássicos para uma nova geração de jogadores e para aqueles que desejam reviver suas memórias. Com um portfólio de produtos que inclui modelos populares como o `MEGANIUM RG353M` e a linha `NEW MEGANIUM` (RG35XX, RG28XX, RG CubeXX, RG 40XXV), a Meganium busca oferecer qualidade e uma experiência autêntica aos seus clientes globalmente através de diversas plataformas de e-commerce.

## Estrutura do Repositório

*   **/data**: Contém os arquivos CSV brutos de vendas e os arquivos de cotação cambial utilizados.
    *   `Meganium_Sales_Data_-_AliExpress.csv`: Dados de vendas do AliExpress.
    *   `Meganium_Sales_Data_-_Etsy.csv`: Dados de vendas da Etsy.
    *   `Meganium_Sales_Data_-_Shopee.csv`: Dados de vendas da Shopee.
    *   `EUR_USD_2024.csv`: Cotações históricas EUR para USD em 2024.
    *   `GBP_USD_2024.csv`: Cotações históricas GBP para USD em 2024.
*   **/insights**: Principais insights coletados com a execução dos prompts no Google Studio AI.
*   **/prompts**: Detalhe dos prompts utilizados para explorar os dados e obter insights valiosos sobre as vendas da empresa Meganium.
*   `README.md`: Este arquivo, fornecendo uma visão geral do projeto.

## Análises Realizadas

As seguintes análises foram conduzidas para extrair insights valiosos dos dados de vendas:

1.  **Consolidação e Limpeza de Dados:**
    *   Combinação dos dados de vendas das três plataformas (AliExpress, Etsy, Shopee).
    *   Padronização de formatos de data e numéricos.

2.  **Conversão Monetária para USD:**
    *   Criação de colunas de valores (`unit_price_usd`, `total_price_usd`, `discount_value_usd`) convertidos para USD utilizando taxas de câmbio históricas diárias (EUR/USD e GBP/USD) para o ano de 2024. Isso permitiu comparações financeiras precisas entre transações em diferentes moedas.

3.  **Análise de Desempenho por Produto (SKU):**
    *   Identificação de volume total vendido, receita bruta (USD), ticket médio por SKU (USD).
    *   Determinação do país campeão de vendas por volume para cada SKU.
    *   Cálculo da idade média dos compradores por SKU.
    *   Avaliação da rentabilidade considerando descontos (porcentagem de desconto sobre receita bruta USD).
    *   Identificação de produtos com potencial para aumento de receita.

4.  **Análise de Desempenho por Plataforma de Venda:**
    *   Comparação da quantidade de vendas, produto mais vendido (volume), receita bruta (USD) e ticket médio (USD) entre AliExpress, Etsy e Shopee.
    *   Análise da proporção de descontos aplicados em cada plataforma.

5.  **Análise de Descontos sobre Produto e Plataforma:**
    *   Análise detalhada do impacto dos descontos, cruzando SKU, plataforma, volume, receita bruta (USD), valor total de desconto (USD) e a porcentagem de desconto sobre a receita.
    *   Investigação da relação entre o percentual de desconto e o volume de vendas.

6.  **Análise Temporal e de Sazonalidade:**
    *   Agrupamento das vendas por mês/ano e trimestre.
    *   Identificação dos meses com maior receita (USD) e maior proporção de descontos.
    *   Análise de tendências de vendas ao longo do período analisado (Q2, Q3, início do Q4 de 2024).

7.  **Análise do Mercado Geográfico:**
    *   Análise de volume de vendas, receita bruta (USD), desconto (USD) e receita líquida (USD) por país e SKU.
    *   Identificação de preferências de produtos em regiões específicas.
    *   Análise da preferência de plataformas de venda por país.

## Conclusões e Próximos Passos

As análises revelaram oportunidades significativas para a Meganium otimizar suas operações de vendas, desde a seleção de produtos e plataformas prioritárias até a calibração de estratégias de desconto e a exploração de mercados geográficos promissores.

O plano de ação detalhado (ver `4. Resumo Executivo - Análise de Vendas Meganium.docx`) fornece um roteiro para a implementação dessas recomendações. Os próximos passos incluem:

1.  **Implementação da Fase 1 do Plano de Ação:** Foco em análises aprofundadas e planejamento inicial.
2.  **Estabelecimento de KPIs e Metas:** Definir métricas claras para acompanhar o progresso das ações.
3.  **Colaboração Interdepartamental:** Engajar as equipes de marketing, operações e finanças para a execução do plano.
4.  **Monitoramento Contínuo:** Realizar revisões periódicas dos dados e ajustar as estratégias conforme necessário.

## Contato

Para mais informações sobre este projeto, entre em contato com Diego Martin Pun Lay Vera em dpunlay@gmail.com.