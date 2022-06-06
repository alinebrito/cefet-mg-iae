# Matlab: Importando dados

Frequentemente, utilizamos o MATLAB para realizar análise de dados, por exemplo, dados de experimentos e de pesquisas em campo. 
Para utilizar esses dados, precisamos importá-los. 

## Importando dados via código

Existem diversos recursos que permitem importar dados no MATLAB, como por exemplo,
a função [readtable](https://www.mathworks.com/help/matlab/ref/readtable.html). 
Para utilizá-la, basta informar o nome do arquivo que desejamos importar. Por exemplo:

```matlab
filename = '2019-2020-destinacao-de-residuos.csv';
dataset = readtable(filename);
```


## Importando dados via assistente de importação
