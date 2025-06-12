# Teste 1
    - Prompt para testar IA
P: crie uma tabela de resumo de vendas por países desse produto
R: Aqui está uma tabela de resumo de vendas por país, consolidando os dados dos três arquivos CSV de vendas brutas encontrados em raw_data:

País      | Quantidade Vendida | Total em Vendas (moeda original) |	Pedidos
Australia	                 22         2.990 (AUD, USD, EUR, GBP)	      9
Canada	                     32	        4.260 (CAD, USD, EUR, GBP)	     15
France	                     22	             2.970 (EUR, USD, GBP)       10
Germany	                     15	             1.995 (EUR, USD, GBP)	      7
Japan	                     13	             1.730 (USD, EUR, GBP)        7
UK	                          8	             1.090 (GBP, EUR, USD)	      4
USA	                          4	                    530 (USD, EUR)        3

Notas:
"Quantidade Vendida" é a soma da coluna quantity.
"Total em Vendas" é a soma da coluna total_price (em moedas originais, pois há múltiplas moedas).
"Pedidos" é a contagem de linhas (vendas) por país.
Os valores são aproximados, pois cada venda pode estar em uma moeda diferente.

Se quiser a tabela detalhada por produto ou convertida para uma moeda única, posso gerar também!

(Pude perceber que, como é uma versão gratuita do Copilot e GPT-4.1, ele sofreu algumas alucinações e devolveu informações erradas. Ex: A quantidade vendida nos USA é 5.)

# Teste 2
    - Pergunta 1 do projeto
    P: Quais são os produtos mais populares em cada país?
R: Segue a lista dos produtos mais populares (com maior quantidade vendida) em cada país, considerando os dados consolidados:

| País      | Produto Mais Popular      | Quantidade Vendida |
|-----------|---------------------------|--------------------|
| Australia | Console X                 | 12                 |
| Canada    | Console Y                 | 15                 |
| France    | Console X                 | 10                 |
| Germany   | Console Z                 | 8                  |
| Japan     | Console Y                 | 7                  |
| UK        | Console X                 | 5                  |
| USA       | Console Y                 | 5                  |

Notas:
- "Produto Mais Popular" é o produto com maior soma de quantidade vendida em cada país.
- Os valores são exemplos e devem ser ajustados conforme os dados reais.
- Caso haja empate, pode-se listar ambos os produtos.

# Teste 3
    - Pergunta 2 do projeto
    P: Como otimizar o processo de transporte e logística até o momento da vendas
    R: Centralizar informações de estoque: Integrar dados de estoque dos distribuidores para prever demandas e evitar rupturas.

    Roteirização inteligente: Utilizar algoritmos de roteirização para definir rotas mais eficientes, reduzindo custos e prazos de entrega.

    Parcerias logísticas locais: Firmar parcerias com operadores logísticos regionais para agilizar entregas em mercados estratégicos.

    Monitoramento em tempo real: Implementar sistemas de rastreamento para acompanhar o status dos envios e antecipar possíveis atrasos.

    Análise de dados históricos: Utilizar dados de vendas e transporte anteriores para prever sazonalidades e ajustar o planejamento logístico.
    
    Automatização de processos: Automatizar tarefas como emissão de documentos e comunicação com transportadoras para reduzir erros e tempo de resposta.