# Anotações de estudo

Cap.1 - Values, Types and Operators

Values - Conjunto de bits sendo eles numeros, texto, funcões e etc...

Types
    Numbers
        Representado por valores numericos como 13, 13.5 ou 2.998e8
        Operações aritmeticas
            Segue o padrão com modulo, multiplicações, divições, soma e subtrações.
            * - Multiplcação
            / - Divisão
            + - Soma
            - - Subtração
            % - Modulo
            Caso necessite de prioridede de calculos o uso do parenteses deve ser aplicado.
        Special Numbers
            Existe 3 valores especiais, Infinity, -Infinity e NaN
    Strings
        Conjunto de carecteres cercados por '', "", ``
        O uso \ indica um utlização espacial para o caracter que o segue como por exemplo \n que é interpretado com um nova linha
            'Texto de exemplo\nseria assim'
            Texto de exemplo
            seria assim
        Caso queria representar algum caractere especial dentro de uma string a \ pode ser utilizada com escape no exemplo abaixo usado para que saida mostre dentro da string o "" e o \n
            "Texto de exemplo \"\\n\"."
            Texto de exemplo "\n".
        Caso tenha a necessidade de juntar strings separada pode se utilizar o operado + para concatenação
            "Bisc"+"oito"
            Biscoito
        A utilização de `` em strings as transforma em Template Literals, a utilização de operações dentro de ${} no interior das Template Literals serão calculadas.
            `metade de 20 é ${20 / 2}`
            metade de 20 é 10
    Unary Operators
        Temos operadores que necessitan de apenas uma entrada para mostrar um resulatado como o typeof que retorna o tipo da entrada utilizada
            console.log(typeof "x")
            string
        Existem operadores que podem receber um ou mais de uma entrada com o - que pode realizar a subtração ou a negativação de um numero
    Boolean Values
        
        

