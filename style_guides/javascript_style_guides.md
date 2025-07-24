# JavaScript Style Guide

```javascript
// Utilize lowercase para nomear arquivos: nome_arquivo.js
```

```javascript
// Use UPPER_SNAKE_CASE para constantes e camelCase para variáveis.
const CONSTANT_NAME = "value" 
let varName = "value"
```

```javascript
// Use espaços entre os operadores e após virgulas.

let x = y + z;
const arr = ["1", "2", "3"];
```

```javascript
/* Em instruções compostas (functions, if/else, for, etc.), use:
    1. Chave inicial no final da linha com espaço antes.
    2. Chave final em nova linha sem espaços. 
*/

function myFunction(params) {
    return ;
}

```

```javascript
// Para objetos:

const obj = {
    string: "Valor",
    number: 100,
    boolean: true,
    null: null
};

```

```javascript
// Evitar linhas com mais de 80 caracteres.

"Por exemplo: esta linha possui mais de oitenta caracteres então deve ser quebrada linhas menores"
```

```html
<!--ADICIONANDO JS NO HTML-->

<script src="arquivo.js"></script>

```

## Boas práticas

- Evitar variáveis globais e usar 'var'. Use variáveis locais com 'let' ou 'const'.
- Declare as variveis no topo do código.
- Inicialize as variáveis. (Evita erro com 'undefined').
- Declare objetos, arrays com 'const' para evitar alterações.
- Evite usar 'new'.
- Use '===' para comparar valores.