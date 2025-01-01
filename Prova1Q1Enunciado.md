## Descrição
Ambrósio fez um exame de sangue e está ansioso por saber o resultado. Você deseja ajudá-lo escrevendo um programa que leia o valor obtido no exame e, de acordo com a tabela abaixo contendo as faixas de valores, informe o resultado do exame.

|Faixa | Resultado|
|---|---|
|Menor que 100 mg/dl | OTIMO|
|De 100 mg/dl a 129 mg/dl | DESEJAVEL|
|De 130 a 159 mg/dl | LIMITROFE|
|De 160 a 189 mg/dl | ALTO|
|Maior ou igual a 190 mg/dl | MUITO ALTO|

## Formato de entrada
Uma linha contendo o valor (inteiro) do colesterol LDL em mg/dl.

## Formato de saída
O programa deve imprimir uma linha contendo mensagem no formato exemplificado abaixo (sem acentos). Considerando como exemplo o valor de 120 mg/dl, teríamos a mensagem:

`ColesterolLDL 120 mg/dl: DESEJAVEL`

Quando o resultado for ALTO ou MUITO ALTO, uma mensagem extra deve ser dada a mensagem “Procure um medico” na linha seguinte ao resultado.
