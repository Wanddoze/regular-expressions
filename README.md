# regular-expressions

## Repositorio 

-- [A-z] Todas letras
-- [0-9] Todos numeros
-- [A-z0-9] ou \w Todas letras, Todos numeros
-- ^ negação da classe

Mais exemplos

- A expressão [a-z] reconhece todas as letras minúsculas.
- A expressão [A-Z] reconhece todas as letras maiúsculas.
- A expressão [A-z] reconhece todas as letras maiúsculas e minúsculas.
- A expressão [A-Z0-9] reconhece todas as letras maiúsculas e números.
- A expressão [a-e] reconhece as letras a, b, c, d e e.

Atalhos para classes mais comuns

- A classe \w recupera todos os caracteres alpha numericos, ou seja, letras e números, mas não acentos ou caracteres especiais. É o equivalente a [a-zA-Z_0-9]
- A classe \W pega TODOS os caracteres que não seja alpha numericos, ou seja, pontuações e espaços.
- A classe \s é o equivalente [ \t\n\x0B\f\r]
- A classe \d é o equivalente [0-9]