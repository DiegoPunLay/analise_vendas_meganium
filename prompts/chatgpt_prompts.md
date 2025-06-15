
PROMPTS NO GOOGLE AI STUDIO

Prompt 1:
Realizar o ajuste dos valores dos produtos e convertir todos os valores em Dolares Americanos (USD) quando o campo "currency" for diferente de "USD".
A conversão deverá ser realizada utilizando como base a data do campo "date_sold".
As cotações se encontram nos arquivos em anexo:
1. Arquivo "EUR_USD_2024" -> Conversão de Euro para Dolar
2. Arquivo "GBP_USD_2024" -> Conversão de GBP para Dolar

---

Prompt 2:
finja que você é um Head de Vendas da Meganium. Quais seriam as principais análises estratégicas que você faria sobre os dados de vendas?

---

Prompt 3:
Realize uma análise de desempenho por produto, criando uma tabela com as colunas a seguir:

1. SKU: SKU do Produto
2. Nome: Nome do Produto
3. Volume: Volume Total Vendido
4. Receita: Receita gerada por SKU
5. Ticket Médio: Ticket Médio por SKU
6. País Campeão: País no qual o produto vendeu mais
7. Idade Média: Idade média dos compradores

Considerar as premissas a seguir na criação da tabela:
1. Ordenar os dados pela coluna "Receita" de forma descrescente
2. Na coluna "País Campeão" preencher só o país com a maior quantidade de vendas do produto  
3. Considerar até a data de hoje para realizar o cálculo da idade dos compradores

Realizar um resumo da análise respondendo as perguntas a seguir:
1. Quais são os produtos que geram mais receita?
2. Quais produtos tem a melhor relação volume e preço?
3. Quais produtos tem uma margem saudável após os descontos?
4. Qual produto tem maior potencial de aumentar nossa receita? Explique a resposta.

Após a criação da tabela, gerar um breve resumo executivo com três ações e recomendações para implementar na companhia com o objetivo de aumentar as vendas e faturamento da empresa. Utilizar uma linguagem direta, sucinta e objetiva para as recomendações.

---

Prompt 4:
Realize uma análise de desempenho por plataforma de venda, criando uma tabela com as colunas a seguir:

1. Plataforma
2. Quantidade de Vendas
3. Produto mais vendido
4. Receita
5. Ticket Médio

Considerar as premissas a seguir na criação da tabela:
1. Ordenar os dados pela coluna "Receita" de forma descrescente

Realizar um resumo da análise respondendo as perguntas a seguir:
1. Qual plataforma gera mais receita?
2. Qual plataforma tem a maior proporção entre valor de desconto "discount_value" em relação ao preço "total_price"?

Após a criação da tabela, gerar um breve resumo executivo com três ações e recomendações para impulsionar as vendas nas plataformas. Utilizar uma linguagem direta, sucinta e objetiva para as recomendações.

---

Prompt 5:
Realizar uma análise de descontos sobre produto e plataforma gerando a tabela a seguir:

1. SKU
2. Nome do Produto
3. Plataforma
4. Volume de vendas
5. Receita Bruta
6. Valor Total Desconto
7. Porcentagem de Desconto sobre Receita Bruta

Premissas:
1. Ordenar a Tabela da seguinte maneira:
    a) Campo "Receita Bruta" de forma descendente
    b) Campo "Porcentagem de Desconto Sobre Receita Bruta" de forma ascendente

Realizar um resumo da análise respondendo as perguntas a seguir:
1. Algum dos produtos teve vendas maiores oferecendo maiores descontos?
2. Tem algum produto que teve um impacto negativo oferecendo um maior desconto?
3. Qual é a plataforma que apresenta a menor performance com os descontos oferecidos?
4. Existe algum padrão no campo "discount_coupon" que possa ser analisado?
5. Existe algum padrão entre o desconto e volume de vendas?

Baseado em todas as informações coletadas sugerir até 3 ações que possam ser implementadas para ajustar os percentuais de desconto por produto e por plataforma.

---

Prompt 6:
Realizar uma análise temporal e de sazonalidade sobre os produtos gerando a tabela a seguir:

1. Mês e Ano (Exemplo: Março 2024)
2. Plataforma
3. Volume de vendas
4. Receita Bruta
5. Trimestre: Trimestre ao qual o mês pertence

Premissas:
1. Ordenar a Tabela pelo campo "Mês e Ano" de Janeiro a Dezembro.

Realizar um resumo da análise respondendo as perguntas a seguir:
1. Qual é o mês onde tivemos a maior receita?
2. Qual é o mês onde foi necessário ter mais descontos para aumentar as vendas?

Baseado em todas as informações coletadas sugerir até 3 ações que possam ser implementadas para melhorar a estratégia de vendas em cada trimestre.

---

Prompt 7:
Realizar uma análise do mercado geográfico sobre os produtos gerando a tabela a seguir:

1. País
2. SKU
3. Nome do Produto
4. Volume de Vendas
5. Receita Bruta
6. Desconto
7. Receita Líquida (Receita Bruta - Desconto)
 
Premissas:
1. Ordenar a Tabela da seguinte maneira:
   a) Pela coluna "País" em ordem alfabético
   b) Pela coluna "Receita Líquida" em ordem decrescente 

Realizar um resumo da análise respondendo as perguntas a seguir:
1. Existem produtos que são mais consumidos em países próximos onde seja possível aprimorar a logística?
2. Existe preferência de uso de alguma plataforma em alguns países? Detalhar a relação

Baseado em todas as informações coletadas sugerir até 3 ações que possam ser implementadas para melhorar a estratégia por localidade.

---

Prompt 8:
O documento em anexo contém todas as sugestões de ações de melhoria para implementar na empresa. 
Revise todas as sugestões de maneira a gerar um documento consolidado com as premissas a seguir:
1. Consolidar recomendações e excluir recomendações duplicadas ou similares
2. Organizar as recomendações dentro de uma sequência lógica temporal
3. Para estimar uma atividade considerar uma equipe de dois analistas de vendas
4. Considerar o foco no aumento de vendas e aprimoramento do processo de transporte e logística até a venda

A estrutura do documento de saída deverá seguir este modelo:
1. Introdução: Breve resumo do objetivo do documento
2. Recomendações consolidadas
3. Tabela de Plano de ação com o detalhe a seguir:
   a) ID: Número sequêncial
   b) Atividade: Descrição da atividade
   c) Prazo: Prazo estimado para implementar a atividade
   d) Observações: Informações adicionais que possam ser úteis para a execução da tarefa
4. O documento deverá ser gerado em formato Microsoft Word
 