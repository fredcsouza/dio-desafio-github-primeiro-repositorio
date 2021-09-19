<h1 align="center">Javascript</h1>

- Valores copiados e por referência

    ```
    Valores primitivos são imutáveis ( copia )

    Valores por referência são mutáveis (array, object, function)
    ```

- Operador ternário

    ```jsx
    condicao ? respostaVerdadeira : respostaFalsa
    ```

- Tipos de Falso

    ```jsx
    false
    0
    "" '' ``
    null
    undefined
    NaN
    ```

- Tipos de funções

    ```jsx
    // Função declarativa
    // Recebe Hoisting
    function teste(){
    	//.....
    }

    -------------------------

    // Function expression
    //First-class objects
    const teste = function() {
    	//...
    }

    -------------------------

    // Arrow function
    // não possui this e arguments
    () => {}

    ```


- Short circuit evaluation

    ```jsx
    const doSomething = () => console.log('OK');
    const isLoggedIn = true;

    isLoggedIn && doSomething();
    ```

- Convert to number

    ```jsx
    const age = '19';
    const ageValueYype = typeof +age;
    // ageValueType = number
    ```