# Integração entre Lua e C++

## 1. O que significa integrar linguagens?

A integração entre linguagens permite que tecnologias diferentes trabalhem juntas dentro de uma mesma aplicação.

Uma aplicação pode utilizar C++ para implementar funcionalidades e Lua para permitir que essas funcionalidades sejam utilizadas por meio de scripts.

## 2. Qual é o papel de cada linguagem?

### C++

C++ pode ser utilizado para desenvolver a estrutura principal do software, implementar funcionalidades e controlar operações que fazem parte da aplicação.

### Lua

Lua é uma linguagem de script leve, que pode ser incorporada a outras aplicações.

Ela permite criar scripts que utilizam funcionalidades disponibilizadas pelo próprio software.

## 3. Como as linguagens se comunicam?

Em uma aplicação que integra Lua e C++, o funcionamento pode seguir este fluxo:

1. Uma funcionalidade é implementada em C++.
2. A aplicação registra ou disponibiliza essa funcionalidade para Lua.
3. Um script Lua chama a função utilizando os parâmetros esperados.
4. A aplicação executa a implementação correspondente.
5. O resultado pode ser retornado ao script.

## 4. Exemplo prático no contexto do NewGC

Durante o estudo da API Lua do NewGC, foi possível observar que funções utilizadas nos scripts são disponibilizadas pela aplicação.

A análise do arquivo `CLuaApi.cpp` permite investigar como determinadas funções são registradas e relacionadas à implementação do software.

Isso ajuda a compreender a relação entre o código interno da aplicação e as funcionalidades disponíveis para quem escreve scripts Lua.

## 5. O que aprendi

- Uma aplicação pode combinar diferentes linguagens de programação.
- Lua pode ser incorporada a softwares desenvolvidos em C++.
- Funções disponibilizadas pela aplicação podem ser utilizadas em scripts.
- A leitura do código-fonte ajuda a entender como uma API funciona internamente.
- A documentação e os testes ajudam a compreender o comportamento das funcionalidades disponíveis.
