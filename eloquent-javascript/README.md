# Anotações de estudo

## Cap.1 - Values, Types and Operators

* Values - Conjunto de bits sendo eles numeros, texto, funcões e etc...

1. Types

    1.1 Numbers

    * Representado por valores numericos como 13, 13.5 ou 2.998e8

    1.1.1 Operações aritmeticas

    * Segue o padrão com modulo, multiplicações, divições, soma e subtrações.

            * - Multiplicação
            / - Divisão
            + - Soma
            - - Subtração
            % - Modulo

    * Caso necessite de prioridede de calculos o uso do parenteses deve ser aplicado.

    1.1.2 Special Numbers

    * Existe 3 valores especiais, Infinity, -Infinity e NaN

    1.2 Strings

    * Conjunto de carecteres cercados por '', "", ``

    * O uso \ indica um utlização espacial para o caracter que o segue como por exemplo \n que é interpretado com um nova linha

            'Texto de exemplo\nseria assim'
            Texto de exemplo
            seria assim

    * Caso queria representar algum caractere especial dentro de uma string a \ pode ser utilizada com escape no exemplo abaixo usado para que saida mostre dentro da string o "" e o \n

            "Texto de exemplo \"\\n\"."
            Texto de exemplo "\n".

    * Caso tenha a necessidade de juntar strings separada pode se utilizar o operado + para concatenação

            "Bisc"+"oito"
            Biscoito

    * A utilização de `` em strings as transforma em Template Literals, a utilização de operações dentro de ${} no interior das Template Literals serão calculadas.

            `metade de 20 é ${20 / 2}`
            metade de 20 é 10

    1.3 Unary Operators

    * Temos operadores que necessitan de apenas uma entrada para mostrar um resulatado como o typeof que retorna o tipo da entrada utilizada

            console.log(typeof "x")
            string

    * Existem operadores que podem receber um ou mais de uma entrada com o - que pode realizar a subtração ou a negativação de um numero

    1.4 Boolean Values

    * Retorna a comparação da entradas com informação de verdadeiro ou falso
    
    * Os seguintes operadores de comparação podem ser utilizados

            > - maior que
            < - menor que
            >= - maior ou igual
            <= - menor ou igual
            == - igual a
            != - diferente de

    1.4.1 Logical Operators

    * Operadores possiveis para serem utilizado com valores boleanos

            && - and
            || - or
            ! - not
    * Existe ainda o operador ternario no caso ? que pode ser utilizado com no exemplo abaixo

            true ? 1 : 2
            false ? 1 : 2
    * sendo o true sera mostrado como resulado o valor a esquerda do : e false o da direita

    1.5 Empty Values

    * Dois valores possíveis null e undefined

    1.6 Automatic Type Conversion

    * O javascript sempre tentar mostrar um resuldo valido convertendo automaticamento o tipo de algumas entradas

            console.log(8 * null)
            // → 0
            console.log("5" - 1)
            // → 4
            console.log("5" + 1)
            // → 51
            console.log("five" * 2)
            // → NaN
            console.log(false == 0)
            // → true

    * Isso se chama type coercion, como no exemplo onde ele tra o resultado da substração de "5" - 1 onde o 5 é um string que é convertida em um numero que de o resultado