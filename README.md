# sockets-c-windows
cliente-servidor
(português-br)

Como executar:

cmd

gcc server.c -o server -l wsock32

server


Porta local: (informe uma porta) (exemplo: 5000)


Abra outro prompt de comando:

cmd

gcc client.c -o client -l wsock32

client

IP do servidor:
(ex: 192.168.0.104)
Porta do servidor: (informe a mesma porta do servidor)

Ficara disponivel enviar mensagem pro servidor

