Stringbetween

1. O que é?

A `Stringbetween` é uma função de manipulação de strings utilizada para extrair um trecho de texto localizado entre dois delimitadores.

2. Parâmetros

| Parâmetro | Descrição |
|---|---|
| `texto` | Texto no qual será realizada a busca. |
| `inicio` | Delimitador que marca o início do trecho. |
| `fim` | Delimitador que marca o final do trecho. |

3. Exemplo de utilização

```lua
local texto = "<titulo>Olá mundo</titulo>"

local resultado = Stringbetween(
    texto,
    "<titulo>",
    "</titulo>"
)

showMessage(resultado)
```
 4. Resultado esperado

```text
Olá mundo
```

 5. O que aprendi

- Manipulação de strings em Lua.
- Busca de trechos específicos dentro de um texto.
- Utilização de parâmetros em funções.
- Armazenamento e utilização de valores retornados.
- Validação do comportamento de uma função por meio de testes.
