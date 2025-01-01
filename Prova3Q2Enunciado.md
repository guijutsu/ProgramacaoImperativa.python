## Descrição
Um grupo grande de pessoas fez várias apostas na Mega Sena e precisa de um programa para ajudá-los a conferir se houve ganhadores. Você foi encarregado de fazer uma versão inicial do programa que indica apenas quantos foram os apostadores que acertaram os 6 números. Nesta versão inicial, são permitidas apenas apostas contendo no máximo 10 números.

## Formato de entrada
Na primeira linha é informado um número inteiro N que representa o número de apostas. Nas N linhas seguintes, são fornecidas as apostas. Cada aposta é formada por 6 a 10 números inteiros separados por vírgulas. Na última linha é fornecido o resultado oficial, também formado por 6 números inteiros, mas neste caso separados por espaços. Por simplicidade, assuma que os números estão ordenados de forma crescente.

## Formato de saída
A saída consiste da string “Total de ganhadores:” seguida por um espaço em branco e do número de apostas que contêm os números do resultado, ou seja, o número de ganhadores.

### Exemplo

**Entrada:**

```
4
1,2,3,4,5,6,7,8,9,10
5,6,7,8,9,10
4,7,8,9,10,11
3,4,5,6,7,8,9
5 6 7 8 9 10
```

**Saída:**
```
Total de ganhadores: 2
```

---

**Entrada:**
```
3
1,3,5,7,9,11
2,4,6,8,10,12,14,15
10,20,30,40,50,55
2 6 8 10 14 15
```

**Saída:**
```
Total de ganhadores: 1
```
