﻿# Desvendando-o-Churn-An-lise-de-Cancelamento

O que o código faz?

Importa e prepara a base de dados:

Importa a biblioteca Pandas para manipulação de dados.
Lê a base de dados CSV "cancelamentos_sample.csv" para a variável tabela.
Remove a coluna "CustomerID" por ser considerada inútil.
Exibe as informações da base de dados para análise.
Limpa e prepara os dados:

Verifica a presença de valores nulos na base de dados.
Elimina linhas com valores nulos para garantir a qualidade dos dados.
Exibe as informações da base de dados após a limpeza.
Analisa a taxa de cancelamento:

Quantifica o número de clientes que cancelaram e os que permaneceram.
Calcula a porcentagem de clientes que cancelaram, fornecendo uma visão geral da taxa de churn.
Explora as causas do cancelamento:

Utiliza gráficos de histograma para visualizar a distribuição de cada coluna em relação ao cancelamento.
Identifica padrões e tendências que podem indicar fatores que contribuem para o cancelamento.
Analisa as seguintes colunas:
duracao_contrato: Clientes com contratos mensais cancelam com mais frequência.
ligacoes_callcenter: Clientes que fazem mais ligações para o call center tendem a cancelar.
dias_atraso: Clientes com atrasos acima de 20 dias apresentam maior taxa de cancelamento.
Aplica filtros para aprofundar a análise:

Exclui clientes com contratos mensais, pois apresentam alto índice de cancelamento.
Filtra clientes que fazem no máximo 4 ligações para o call center.
Seleciona clientes com atrasos de até 20 dias.
Repete a análise da taxa de cancelamento e das causas para este grupo filtrado.
Observações:

O código utiliza a biblioteca plotly para gerar gráficos, que podem ser visualizados no notebook.
O código pode ser adaptado para analisar outras bases de dados e identificar fatores específicos que contribuem para o churn em seu negócio.
É importante ter em mente que a análise de cancelamento é um processo contínuo que requer monitoramento constante e ajustes nas estratégias de retenção de clientes.
Benefícios da Análise de Cancelamento:

Compreensão profunda dos motivos do churn: Identifique os principais fatores que levam os clientes a cancelar seus contratos.
Desenvolvimento de estratégias direcionadas: Tome medidas eficazes para reduzir o churn e aumentar a retenção de clientes.
Melhoria da experiência do cliente: Resolva problemas e crie experiências positivas para seus clientes, diminuindo a probabilidade de cancelamento.
Otimização de recursos: Direcione seus esforços e investimentos para iniciativas que realmente impactam a retenção de clientes.
Conclusão:

Este código oferece uma ferramenta valiosa para empresas que buscam reduzir o churn e aumentar a retenção de clientes. Através da análise detalhada dos dados de cancelamento, você pode identificar padrões, compreender os motivos do churn e desenvolver estratégias eficazes para manter seus clientes satisfeitos e engajados.
