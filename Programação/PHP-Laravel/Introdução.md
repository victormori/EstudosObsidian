O PHP (Hypertext Preprocessor) é uma das linguagens de programação mais populares do mundo, projetada principalmente para o desenvolvimento web. É uma linguagem de script de código aberto que roda no lado do servidor, o que significa que ela processa os dados antes de entregar a página (como HTML) para o navegador do usuário. [[1]
## Documentação Oficial:
https://www.php.net/manual/pt_BR/

Usuário → Apache → PHP → Banco de Dados → PHP → HTML → Apache → Usuário

### Exemplo básico de um código PHP dentro do HTML 

```php 
	<?php ?> //é utilizado para delimitar que o código escrito é em PHP, tanto em um código PHP quanto dentro de um HTML como no exemplo abaixo:
	
	<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aula de PHP</title>
</head>
<body>
    <h1>Testando PHP</h1>
	<?php
        echo "<h2>Olá, Mundo!</h2>"; 
    ?>
</body>
</html>
```
	
	