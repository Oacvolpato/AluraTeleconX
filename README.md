# AluraTeleconX

Descrição do caso:
Você foi contratado como assistente de análise de dados na Telecom X e fará parte do projeto "Churn de Clientes". A empresa enfrenta um alto índice de cancelamentos e precisa entender os fatores que levam à perda de clientes.

Seu desafio será coletar, tratar e analisar os dados, utilizando Python e suas principais bibliotecas para extrair insights valiosos. A partir da sua análise, os demais colegas da  equipe de Data Science poderá avançar para modelos preditivos e desenvolver estratégias para reduzir a evasão.

Limpeza e tratamento de dados:
Inicialmente os dados foram importados do dataset utilizando a biblioteca pandas para leitura no formato CSV/JSON, em seguida os dados tiveram seus tipos verificados, com tratamento de casos inesperados e formatos foram corrigidos.

Análise exploratória de dados:
O dado chave que justifica a criação do desafio foi a taxa de 27% de churn que a empresa estava encontrando, representando um problema significativo e indicando que mudanças estratégicas deveriam ocorrer.

Analise por perfil de cliente:
Foram identificados dois pontos relevantes à taxa de churn: clientes que utilizam o contrato mensal e não contratam serviços adicionais possuem uma taxa de churn significativamente elevada.

Análise financeira:
Os dados refletem a análise de perfil de clientes, onde clientes com fatura mensal com valor elevado possuem menor taxa de churn, e que clientes antigos tendem a acumular mais gastos.

Perfil de evasão:
O principal perfil de cliente que abandona os serviços são clientes de contrato mensal com baixo gasto acumulado.

Conclusão:
O tempo de contrato é chave para a taxa de churn, onde planos anuais possuem alta taxa de retenção. É importante notar que o pagamento eletrônico também está relacionado à taxa de churn.

Dessa maneira seria interessante incentivar contratos anuais, seja através da migração de contratos mensais para anuais ou pelo captação de novos contratos anuais através de benefícios e campanhas publicitárias.
