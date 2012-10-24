reconnect.bat
=============

Reconecta uma conexão DialUp no Windows

## Specs
* Feito no SO : Windows XP SP2
* Testado no SO : Windows XP SP2, Windows XP SP3, Windows Embedded XP
* Linguagem Utilizada : Batch Script

## Motivation
Esse script foi feito em Batch para reconectar conexões 3G, mas você pode utilizar com qualquer conexão Dial-Up.

## How To
Você precisa apenas dizer qual a conexão ele deve testar e agendar uma tarefa com um tempo a sua necessidade.
Para determinar a conexão a ser testar altere a linha 10.

```
rasdial INSERTTHECONNECTIONHERE
```

No meu caso eu rodo a tarefa a cada 10 minutos e encerro a tarefa se não funcionar por 5 minutos.
