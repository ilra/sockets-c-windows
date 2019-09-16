# sockets-c-windows

## Descrição:</b>
cliente-servidor  <br>
(português-br)  <br>
<br>

FONTE: http://www.professordiovani.com.br/sd/Sockets_cplus.htm

## Como executar:<br>
Abra o prompt de comando:

-------------------------------------------
<code>cmd</code>  

<code>gcc server.c -o server -l wsock32</code>  

<code>server</code>  

------------------------------------------

Porta local: (exemplo: 5000)  
<br>
<br>
Abra outro prompt de comando:  

-------------------------------------------
<code>cmd</code>   

<code>gcc client.c -o client -l wsock32</code>   
  
<code>client </code>

-------------------------------------------
IP do servidor: (ex: 192.168.0.3)  
  
Porta do servidor: (informe a mesma porta colocada no primeiro prompt)  
  
Ficara disponivel enviar mensagem pro servidor<br>
<br>
<br>
### EXEMPLO:  
![alt text](https://github.com/erikalira/sockets-c-windows/blob/master/exemplo.png?raw=true)


