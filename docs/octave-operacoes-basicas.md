# Octave: Variáveis e Operações Básicas


# Variáveis e Expressões

As [variáveis](https://octave.org/doc/v4.2.0/Variables.html) permitem "dar nomes" aos valores para consultarmos  posteriormente. Logo, é importante escolher nomes claros e objetivos. O nome de uma variável pode incluir um conjunto de letras, digitos, e *underscores* (isto é, `_`). Além disso, o primeiro caracter não pode ser um dígito. 

Para atribuir um valor para uma variável utilizamos o sinal `=`, denominado [operador de atribuição](https://octave.org/doc/v4.2.0/Assignment-Ops.html#Assignment-Ops). Em outra palavras, uma atribuição é uma expressão que armazena um valor numa variável. Exemplos:

```matlab
x = 10
y = 20
resultado = x + y
```
```matlab
nome_completo = "Maria da Silva"
```

__Palavras reservadas:__ Variáveis que começam e terminam com dois *underscores* são utilizadas internamente pelo Octave. Logo, não devemos utilizar esta sintaxe. Por exemplo:

```matlab
__foo_bar_baz__
```

__Variavel ans:__ Se realizarmos uma operação e não atribuirmos o valor para uma variável, o resultado é atribuido para uma variável chamada `ans` na área de trabalho. Em outras palavras, esta variável contém o resultado do último cálculo.

```matlab
>> 10 + 20
ans =  30
```

# Tipos

As variáveis não tem um tipo fixo no Octave. Logo, podemos armazenar um valor numérico numa variável e no passo seguinte armazenar uma string. Por exemplo:

```matlab
x = 10
x = "Maria"
```

Entretanto,  __isso não é uma boa prática__. Adicione variáveis  conforme o contexto. Dessa forma, o seu código ficará legível e organizado.
