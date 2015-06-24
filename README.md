# POA Do Silício Guia de estilo JavaScript 

*Padrão de desenvolvimento com JS*


## <a name='table-of-contents'>Índice</a>

  1. [Variáveis](#variaveis)


## <a name='variaveis'>Variáveis</a>

 - Sempre use `var` para declarar variáveis. Não fazer isso irá resultar em variáveis globais. 

    ```javascript
    // ruim
    eventos = new GetEventos();

    // bom
    var eventos = new GetEventos();
    ```

 - Use apenas um `var` para declarar mais de uma variável

    ```javascript
    // ruim
    var eventos = GetEventos();
    var enviaEmail = true;
    var dia = 15;

    // bom
    var eventos = GetEventos(),
        enviaEmail = true,
        dia = 15;
    ```


