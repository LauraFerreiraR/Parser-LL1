# Parser LL(1)

Implementação de um **Parser Preditivo LL(1)** desenvolvido em **C# (.NET)** para a disciplina de Compiladores do curso de Ciência da Computação.

O projeto realiza a análise sintática de uma sequência de tokens utilizando uma **tabela de parsing LL(1)** carregada a partir de um arquivo CSV, verificando se a entrada está de acordo com a gramática definida.

---

## Objetivo

Este projeto tem como objetivo demonstrar o funcionamento de um analisador sintático LL(1), aplicando conceitos fundamentais de construção de compiladores, como:

- Gramáticas Livres de Contexto (GLC)
- Parser Preditivo LL(1)
- Pilha de análise sintática
- Tabela de Parsing
- Validação de cadeias de entrada

---

## Funcionalidades

- Leitura da tabela LL(1) a partir de um arquivo CSV
- Análise sintática utilizando pilha
- Validação de sequências de tokens
- Identificação de erros sintáticos
- Estrutura simples para adaptação a outras gramáticas

---

## Tecnologias Utilizadas

- C#
- .NET
- CSV
- Estruturas de Dados (Pilha)
- Teoria dos Compiladores

---

## Estrutura do Projeto

```text
Parser-LL1
│
├── SimpleInterpreter/
│   ├── LL1Parser.cs
│   ├── LL1ParserTests.cs
│   ├── Program.cs
│   └── SimpleInterpreter.csproj
│
├── parse_table.csv
├── input.txt
└── SimpleParser.sln
```

---

## Como executar

1. Clone o repositório

```bash
git clone https://github.com/LauraFerreiraR/Parser-LL1.git
```

2. Abra a solução no Visual Studio

```
SimpleParser.sln
```

3. Execute o projeto.

O programa utilizará:

- `parse_table.csv` como tabela de parsing;
- `input.txt` como entrada para análise.

---

## Exemplo de Entrada

```
VAR AT NUM EOF
```

---

## Resultado Esperado

```
Entrada aceita com sucesso!
Análise sintática concluída.
```

Caso a sequência de tokens não pertença à gramática, o parser informará um erro sintático.

---

## Conceitos Aplicados

- Construção de Compiladores
- Análise Sintática
- Gramáticas Livres de Contexto
- Parser LL(1)
- Parsing Preditivo
- Estruturas de Dados
- Linguagens Formais

---

## Melhorias Futuras

- Implementação de um analisador léxico (Lexer)
- Geração automática da tabela LL(1)
- Visualização da árvore sintática
- Melhor tratamento de erros
- Ampliação da cobertura de testes

---


Graduada em Ciência da Computação

Projeto desenvolvido para a disciplina de **Compiladores**.
