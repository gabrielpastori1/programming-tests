### Objetivo:
Enviar o `body` e continuar executando o PHP

### Solução
```php
// Get the size of the output.
$size = ob_get_length();

header("Content-Length: {$size}");
header("Connection: close");

ob_end_flush();
ob_flush();
flush();
```
