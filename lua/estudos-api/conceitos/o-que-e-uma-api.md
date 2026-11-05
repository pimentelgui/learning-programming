# O que é uma API?

## 1. Definição

API é a sigla para *Application Programming Interface*, ou Interface de Programação de Aplicações.

É um conjunto de regras e funcionalidades que permite que diferentes partes de um software se comuniquem e utilizem recursos umas das outras.

Em vez de precisar conhecer todos os detalhes internos de uma aplicação, um programador pode utilizar as funcionalidades disponibilizadas por sua API.

## 2. Como funciona?

Uma API funciona como uma interface entre quem solicita uma operação e quem executa essa operação.

Por exemplo:

1. Um programa solicita uma determinada funcionalidade.
2. A API recebe essa solicitação.
3. A aplicação executa a operação correspondente.
4. O resultado é disponibilizado para quem fez a solicitação.

## 3. Exemplo na programação

Imagine uma aplicação que disponibiliza uma função chamada `somar`:

```lua
local resultado = somar(10, 20)

showMessage(resultado)
```

Nesse exemplo, o script utiliza uma funcionalidade disponibilizada pela aplicação sem precisar conhecer sua implementação interna.

## 4. Relação entre Lua e C++

Uma aplicação pode disponibilizar funções implementadas em C++ para que sejam utilizadas por scripts escritos em Lua.

Nesse cenário:

- **C++:** pode conter a implementação das funcionalidades.
- **API:** disponibiliza essas funcionalidades para utilização.
- **Lua:** permite chamar as funções disponibilizadas pela aplicação.

Essa integração permite ampliar as possibilidades de um software por meio de scripts.

## 5. O que aprendi

Uma API não é necessariamente um programa independente. Ela pode ser uma interface disponibilizada por uma aplicação para permitir que outras partes do sistema utilizem suas funcionalidades.

Também compreendi que diferentes linguagens podem trabalhar juntas, cada uma desempenhando um papel dentro de uma aplicação.
