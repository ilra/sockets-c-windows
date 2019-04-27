# sockets-c-windows
cliente-servidor
(português-br)

Como executar:

cmd <br />
gcc server.c -o server -l wsock32  <br />
 <br />
server <br />
<br />
Porta local: (informe uma porta) (exemplo: 5000)
<br />
<br />


Abra outro prompt de comando: <br />
 <br />
cmd  <br />

gcc client.c -o client -l wsock32 <br />
 <br />
client <br />
 <br />
IP do servidor: <br />
(ex: 192.168.0.104) <br />
Porta do servidor: (informe a mesma porta do servidor) <br />
 <br />
Ficara disponivel enviar mensagem pro servidor <br />
 <br />
 <br />
 EXEMPLO: <br />
![alt text](https://raw.githubusercontent.com/ilra/sockets-c-windows/master/exemplo.png)
