## Descrição
A empresa de abastecimento de gás européia está promovendo uma campanha de conscientização de recursos. Para incentivar a economia de gás, a empresa alterou os preços de seu fornecimento de forma que, proporcionalmente, aqueles clientes que consumirem menos gás paguem menos pelo metro cúbico.

Todo cliente paga mensalmente uma assinatura de R$ 5, que inclui uma franquia de 10 m3 de gás.Isto é, para qualquer consumo entre 0 e 10 m3, o consumidor paga a mesma quantia de R$ 5 reais (note que o valor da assinatura deve ser pago mesmo que o consumidor não tenha consumido gás). Acima de 10 m3, cada metro cúbico subsequente tem um valor diferente, dependendo da faixa de consumo. A cobrança é feita apenas por quantidades inteiras de metros cúbicos consumidos.

A tabela abaixo especifica o preço por metro cúbico para cada faixa de consumo:

|Faixa de consumo($m^3$)|Preço(por $m^3$)|
|--|--|
|Até 10|Incluído na franquia|
|11 a 50|R$1|
|51 a 80|R$2|
|81 em diante|R$3|

Assim, por exemplo, se o consumo foi de 150 m3, o valor da conta é:

- 5 reais da assinatura básica
- 40 reais pelo consumo no intervalo 11 - 50 m3
- 60 reais pelo consumo no intervalo 51 - 80 m3
- 150 reais pelo consumo no intervalo 81 - 150 m3

## Formato de entrada
A única linha da entrada contém um único inteiro N, indicando o consumo de gás da residência, em m3.

## Formato de saída
Seu programa deve imprimir uma única linha, contendo o valor da conta de gás daquela residência.

