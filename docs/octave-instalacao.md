 # Matlab/Octave: Instalação e Configuração

[MATLAB](https://www.mathworks.com/products/matlab.html) é uma plataforma  utilizada para analisar dados, desenvolver algoritmos, e criar modelos. Logo, MATLAB é popular na engenharia e em pesquisas científicas. 

[Octave](https://www.gnu.org/software/octave) é uma plataforma similar, compatível com a sintaxe do MATLAB. Além disso, Octave é um software gratuito.

## Instalação:

No decorrer da disciplina, vamos utilizar o Octave e MATLAB. 

Para instalar o Octave, basta fazer o download do instalador compatível com o seu sistema operacional e seguir as instruções para instalação:

> https://www.gnu.org/software/octave/download

Se você preferir utilizar o MATLAB, o procedimento é o mesmo. Porém, uma licença é requerida.

> https://www.mathworks.com/products/get-matlab.html

## Criando Scripts:

* Os scripts do Octave possuem a extensão `".m"` (ex.: `arquivo.m`). Eles são adicionados numa pasta padrão que é mostrada no canto superior esquerdo da interface.

* Para alterar a pasta para armazenar os scripts, basta pressionar o botão de configuração e definir um novo diretório.

* Existem três opções para criar um novo script:
    
    * Através do menu `Arquivo > Novo > Novo Script`
    * Através do botão `Novo Script`
    * Através do atalho `ctrl + N`

* Para salvar o script:

     * Menu `Arquivo > Salvar arquivo`
     * Através do atalho `ctrl + S`

* Para executar o script:
    * Acesse a aba `Janela de Comandos`, digite o nome do script no console, e pressione `enter`.

    * Existe também uma opção no menu `Executar > Salvar arquivo e executá-lo`, assim como o atalho `F5`.

## Documentação e Ajuda

Podemos acessar a documentação do Octave no [site oficial](https://octave.org/doc/v4.2.0). 

Além disso, podemos consultar a documentação através dos comandos [`help` e `doc`](https://octave.org/doc/v4.2.0/Getting-Help.html). 
O comando `doc` mostra a documentação completa, enquanto o comando `help` mostra uma versão resumina da documentação na janela de comandos:

```matlab
doc plot
```

```matlab
help plot
```

Por fim, podemos utilizar o comando `lookfor` para buscar por uma palavra na documentação. Resumindo, este comando lista os tópicos de ajuda que incluem a string informada. Por exemplo:

```matlab
lookfor plot
```