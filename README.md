# Otimização de hiperparâmetros de modelos de Machine Learning

Neste projeto, vamos explorar diversas técnicas de otimização de hiperparâmetros de modelos de Machine Learning, utilizadas para classificar clientes inadimplentes em uma empresa de empréstimo de automóveis. Vamos utilizar essas técnicas para melhorar nossos modelos a partir da alteração de seus hiperparâmetros e analisar os resultados obtidos.

Para isso, vamos utilizar as bibliotecas Pandas, scikit-learn, matplotlib, scikit-optimize, plotly e numpy. Escrevi o código num notebook do Google Colab e usei a tabela de dados abaixo:

[dados_inadimplencia.csv](https://github.com/mths-andrade/otimizacao_ml/blob/7992fcaf78c149214d5183934e30bd5a75b6f8b2/dados_inadimplencia.csv)

Para compreender o projeto que está sendo desenvolvido, é essencial conhecer os dados que estão sendo trabalhados. Compreender quais variáveis estão sendo inseridas em um modelo de machine learning ajuda a interpretar o resultado devolvido ao final do processo. Abaixo, você pode encontrar o dicionário dos dados usados durante o curso.

'receita_cliente': Renda do cliente em R$

'anuidade_emprestimo': Valor anual da taxa de juros do empréstimo em $

'anos_casa_propria': Idade da propriedade do cliente em anos

'telefone_trab': Acessibilidade do número de telefone comercial (1 indica Sim e 0 indica Não)

'avaliacao_cidade': Classificação da cidade do cliente: 3 para excelente, 2 para bom e 1 para médio.

'score_1': Pontuação originada de uma fonte externa. Este é um escore normalizado.

'score_2': Pontuação originada de uma fonte externa. Este é um escore normalizado.

'score_3': Pontuação originada de uma fonte externa. Este é um escore normalizado.

'score_social': Quantidade de amigos/familiares do cliente que não cumpriram com pagamentos de empréstimos nos últimos 60 dias.

'troca_telefone': Quantidade de dias antes do pedido de empréstimo em que o cliente mudou seu número de telefone.

'inadimplente': 1 indica que o cliente não honrou com o pagamento do empréstimo, e 0 indica o contrário.
