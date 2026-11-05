
# Stringreplace — Substituição de trechos em uma string

### 1. O que é?

A substituição de texto permite localizar um trecho dentro de uma string e substituí-lo por outro.

Em Lua, essa operação pode ser realizada com a função `string.gsub()`.

### 2. Conceito e parâmetros

| Parâmetro | Descrição |
|---|---|
| `texto` | Texto original que será analisado. |
| `antigo` | Trecho que será substituído. |
| `novo` | Novo conteúdo que será inserido. |

### 3. Exemplo de utilização

```lua
local texto = "Olá mundo"

local resultado = string.gsub(texto, "mundo", "Lua")

print(resultado)
```

### 4. Resultado esperado

```text
Olá Lua
```

### 5. O que aprendi

- Utilização da função `string.gsub()` da biblioteca padrão do Lua.
- Substituição de trechos em strings.
- Passagem de parâmetros para funções.
- Armazenamento de resultados em variáveis.
- Manipulação de textos com funções da linguagem Lua.

**Observação:** `string.gsub()` interpreta o trecho de busca como um padrão Lua, não necessariamente como texto literal.
