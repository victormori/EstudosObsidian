Pra criarmos variáveis é necessário utilizar $

```php
<?php ?>

$idade = 3; //tipo (int)inteiro
$nome = "Victor"; //tipo string
$probabilidade = true; // tipo booleano (verdadeiro ou falso)
$preco = 100.50; // tipo Real (float ou double)

``` 

No PHP os tipos das variáveis são definidas por coerção, ou seja, se eu der um valor de um número, ele automaticamente vai defini-la como inteira.

## Tipos primitivos 

- inteiro (int).
- Real (real, float ou double).
- Caractere (string)
- Booleano (não existe um typecast para booleano, true = 1; false = 0;)

## TypeCast

Como o PHP não é fortemente tipado, ele define as variáveis por coerção, mas caso seja necessário tipar uma variável utilizamos parênteses com o tipo desejado dentro dele, um exemplo: 

```php
<?php ?>

$nome = (string) "Victor";
```
