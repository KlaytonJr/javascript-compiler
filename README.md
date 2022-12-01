# Compilador JavaScript

Desenolvido para a disciplina de Compiladores da Universidade Estadual da Paraíba (UEPB)

## Pré requisitos para rodar

- Ter o Java SDK instalado e configurado nas variáveis de ambiente
- Ter o JavaCC instalado e configurado nas variáveis de ambiente

[Link do vídeo de instalação e configuração do JAVACC](https://www.youtube.com/watch?v=lVq3kFTkeWg)

<br />

## Executar este projeto

Primeiro roda o javacc do arquivo .jj (no terminal)

```
javacc javascript.jj
```

Depois, compila o arquivo gerado com o nome da classe do .jj, que neste projeto nomeamos idem como javascript

```
javac javascript.java
```

Por fim roda o programa compilado

```
java javascript
```

<br />

## Checklist

- [x]  Tipos básicos: string, números (inteiro e real)
- [x]  Atribuições
- [x]  Comando de entrada e saída
- [X]  Expressões
- [X]  operadores relacionais, aritméticos e booleanos
- [X]  Estrutura condicional simples e composta
- [X]  Um tipo de laço
- [X]  Declaração de funções
- [X]  Chamada de funções

<br />
<br />

### Executar JAVACC qualquer

Primeiro roda o javacc do arquivo .jj (no terminal)

```
javacc nomeDoArquivo.jj
```

Depois, compila o arquivo gerado com o nome da classe do .jj

```
javac nomeDoArquivo.java
```

Por fim roda o programa compilado

```
java nomeDoPrograma
```
