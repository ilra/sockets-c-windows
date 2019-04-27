# sockets-c-windows

## Descrição:</b>

cliente-servidor  
(português-br)  

## Como executar:  

<code>cmd</code>  

<code>gcc server.c -o server -l wsock32</code>  

<code>server</code>  

Porta local: (informe uma porta) (exemplo: 5000)  
  
  
Abra outro prompt de comando:  
  
<code>cmd</code>   

<code>gcc client.c -o client -l wsock32</code>   
  
<code>client </code>   
  
IP do servidor:  
(ex: 192.168.0.104)  
  
Porta do servidor: (informe a mesma porta do servidor)  
  
Ficara disponivel enviar mensagem pro servidor  
  
  
 EXEMPLO:  
   
![alt text](https://raw.githubusercontent.com/ilra/sockets-c-windows/master/exemplo.png)
