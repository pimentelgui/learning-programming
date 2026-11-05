
# Stringstarts — Verificação do início de uma string

### 1. O que é?

A verificação de prefixo permite identificar se uma string começa com determinado trecho de texto.

Esse tipo de operação pode ser utilizado para verificar prefixos de URLs, códigos e padrões textuais.

### 2. Conceito e parâmetros

| Parâmetro | Descrição |
|---|---|
| `texto` | Texto que será analisado. |
| `prefixo` | Trecho que será procurado no início do texto. |

### 3. Exemplo de utilização

```lua
local function startsWith(texto, prefixo)
    return string.sub(texto, 1, #prefixo) == prefixo
end

local url = "https://exemplo.com"

local resultado = startsWith(url, "https://")

print(resultado)
```

### 4. Resultado esperado

```text
true
```

### 5. O que aprendi

- Verificação de padrões no início de uma string.
- Utilização da função `string.sub()` da biblioteca padrão do Lua.
- Comparação de strings com o operador `==`.
- Utilização do operador `#` para obter o tamanho de uma string.
- Aplicação de funções auxiliares para reutilizar operações.
