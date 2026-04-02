# una-ihcux-lista04

# SistemaRobusto

## Descrição
Este projeto simula um sistema de cadastro que solicita a idade do usuário e valida a entrada de dados.

## Objetivo
Demonstrar a 5ª Heurística de Nielsen: **Prevenção de Erros**.

## O que é try-catch?
O `try-catch` é uma estrutura utilizada em C# para tratar erros que podem acontecer durante a execução do programa.

- O bloco `try` contém o código que pode gerar erro.
- O bloco `catch` captura esse erro, impedindo que o programa quebre.
- O bloco `finally` é executado sempre, independentemente de erro ou sucesso.

## Como isso se conecta com a Prevenção de Erros?
No projeto, o sistema pede que o usuário digite sua idade. Esse valor deve ser um número.

Se o usuário digitar letras (como "vinte"), ocorre um erro na conversão (`int.Parse`).

Sem o `try-catch`, o programa fecharia com um erro técnico.

Com o `try-catch`, o sistema:
- evita que o programa quebre
- mostra uma mensagem clara e amigável
- orienta o usuário a corrigir o erro

Exemplo de mensagem:
"[ERRO DE UX]: Você digitou letras em um campo que só aceita números!"

## Conclusão
O uso do `try-catch` melhora a experiência do usuário, prevenindo erros e fornecendo feedback adequado, em vez de falhas técnicas.
