# Audiobook-app-deep-learning
Machine learning algorithm based on our available data that can predict if a customer will buy again from the Audiobook company.


  A idéia principal é que, se um cliente tem uma baixa probabilidade de voltar, não há razão para gastar dinheiro em propaganda para ele. Se concentrarmos nossos esforços SOMENTE nos clientes que provavelmente serão convertidos novamente, poderemos fazer grandes economias. Além disso, esse modelo pode identificar as métricas mais importantes para que um cliente volte novamente. A identificação de novos clientes cria oportunidades de valor e crescimento.
Você tem um .csv resumindo os dados. 
	Existem várias variáveis: ID do cliente, duração do livro em mins_avg (média de todas as compras), duração do livro em minutos_sum (soma de todas as compras), preço pago_avg (média de todas as compras), preço pago_sum (soma de todas as compras), revisão ( uma variável booleana), Revisão (de 10), Total de minutos ouvidos, Conclusão (de 0 a 1), Solicitações de suporte (número) e Última visita menos a data de compra (em dias).

  Portanto, essas são as entradas (excluindo o ID do cliente, pois é completamente arbitrário. É mais como um nome do que um número).Os destinos são uma variável booleana (então 0 ou 1). Estamos levando um período de 2 anos em nossos insumos e os próximos 6 meses como metas. Então, de fato, estamos prevendo se: com base nos últimos 2 anos de atividade e engajamento, um cliente se converterá nos próximos 6 meses. 6 meses parece um tempo razoável. Se eles não se converterem após 6 meses, é provável que tenham procurado um concorrente ou não gostaram da maneira de digerir informações do Audiobook.

## A tarefa é simples: 
  Criar um algoritmo de aprendizado de máquina, capaz de prever se um cliente comprará novamente.

## Este é um problema de classificação com duas classes: 
  Não comprará e comprará, representado por 0s e 1s.
