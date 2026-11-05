# Stringends — Verificação do final de uma string

### 1. O que é?

A verificação de sufixo permite identificar se uma string termina com determinado trecho de texto.

Esse tipo de operação é útil, por exemplo, para verificar extensões de arquivos, terminações de URLs e padrões textuais.

### 2. Conceito e parâmetros

| Parâmetro | Descrição |
|---|---|
| `texto` | Texto que será analisado. |
| `sufixo` | Trecho que será procurado no final do texto. |

### 3. Exemplo de utilização

```lua
local function endsWith(texto, sufixo)
    if sufixo == "" then
        return true
    end

    return string.sub(texto, -#sufixo) == sufixo
end

local arquivo = "imagem.png"

local resultado = endsWith(arquivo, ".png")

print(resultado)
```

### 4. Resultado esperado

```text
true
```

### 5. O que aprendi

- Verificação de padrões no final de uma string.
- Utilização da função `string.sub()` da biblioteca padrão do Lua.
- Comparação de strings com o operador `==`.
- Utilização do operador `#` para obter o tamanho de uma string.
- Aplicação de funções auxiliares para reutilizar operações.
