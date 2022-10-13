# Octave: Matriz e Vetores


## Declaração


Vetores e matrizes são os estrutura básicas para a análise numérica. 

Para criar uma __[matriz](https://octave.org/doc/v4.0.1/Matrices.html)__  separamos as colunas com espaço ou vírgula (``,``). Para definir uma nova linha na matriz utilizamos ponto e vírgula (``;``). O tamanho da matriz é determinado automaticamente, ou seja, não precisamos declarar as dimensões. Por exemplo, o comando abaixo cria uma matriz 2x2:

```matlab
m1 = [1 2; 3 4]
```

```matlab
1   2
3   4
```

Para criar uma vetor com quatro elementos em uma única linha, utilizamos uma vírgula (``,``) ou um espaço para separar os elementos. Exemplo:

```matlab
v1 = [1 2 3 4]
```

## Operações Básicas
Utilizando o MATLAB/Octave, podemos processar todos os valores de uma matriz usando um 
único operador aritmético ou função. Por exemplo, considere a seguinte matriz:

```matlab
1     3     5
2     4     6
7     8    10
```
Podemos declará-la da seguinte forma no Octave:
```matlab 
m1  =  [1 3 5; 2 4 6; 7 8 10]
```

Em seguida, podemos realizar a seguinte operação:

```matlab 
m1 + 10
```

Resultado:
```matlab 
ans =
   11   13   15
   12   14   16
   17   18   20
```


## Acessando Elementos

Para acessar um elemento na linha primeira linha e primeira coluna da matriz `m1` utilizamos o seguinte comando:

```matlab 
m1(1,1)
```
Resultado:
```matlab 
ans =  1
```

Da mesma forma, para acessar o elemento da segunda linha e primeira coluna utilizamos o comando:

```matlab 
m1(2,1)
```

Resultado:
```matlab 
ans =  3
```

Observe que o índice começa com o valor 1. O primeiro parâmetro refere-se à linha, e o segundo parâmetro refere-se à coluna. 

Para modificar um valor na matriz, basta utilizar o operador de atribuição `=`. Por exemplo, o comando abaixo altera o elemento da linha 2 e coluna 1 para `100`:

```matlab 
m1(2,1) = 100
```

```matlab 
m1 =
     1     3     5
   100     4     6
     7     8    10
```

## Matriz Transposta

Obtemos uma matriz transposta trocando as linhas por colunas. No Octave, podemos transpor uma matriz utilizando aspas simples (`'`). Por exemplo:

```matlab 
m1'
```

Resultado:
```matlab 
ans =
    1    2    7
    3    4    8
    5    6   10
```
