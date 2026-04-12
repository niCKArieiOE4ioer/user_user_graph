# Ideias iniciais


## Operações matemáticas

O jogador precisa avaliar o resultado de uma expressão montada com números sorteados. A cada acerto, a quantidade de números aumenta.

No começo só entram somas. Depois viriam subtrações, multiplicações e divisões. Ainda não sei qual é a melhor forma de encaixar isso; veja alguns problemas:

- Numa expressão mista, a multiplicação tem precedência. Aplicando as contas na ordem em que aparecem, o resultado sai errado.
- Multiplicar números grandes é inviável para cálculo mental: três dígitos já deixam a conta pesada.
- Divisões encadeadas que não dão resultado inteiro tornam a resposta ambígua.

Exemplo com números sorteados:

```
55 + 12
(acerto)

(próxima rodada)
55 + 12 + 1
(acerto)

(próxima rodada)
55 + 12 + 1 + 97
(erro)

Você acertou 2 vez(es)
Resultado correto: 165
```


## Versão em Julia

Para conferir a versão da linguagem instalada, rode o comando de versão.

Usei a versão 1.10.4.


## Outros recursos

O quadro de tarefas do projeto fica num serviço de quadros online.

Há uma gravação de demonstração do jogo.

E a página oficial de download da linguagem.


## Outras versões

Existe também a versão em Kotlin.

E a versão em Elixir.