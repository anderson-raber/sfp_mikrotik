# sfp_mikrotik

## Template para monitoramento de interfaces SFP de equipamentos Mikrotik

## Monitora:
 - Tx
 - RX
 - Temperatura

## Triggers:
 - Variação de sinal de tx/x
 - Alarme de temperatura
 
 # Importante:
 Criar uma nova expressão regular no zabbix, nomear "sfp", tipo de expressão "resultado VERDADEIRO", expressão ^[Ss]fp
 
 ficando assim:
 
 ![image](https://github.com/anderson-raber/sfp_mikrotik/blob/master/Anota%C3%A7%C3%A3o%202019-08-28%20105457.png)

 ![image](https://github.com/anderson-raber/sfp_mikrotik/blob/master/Anota%C3%A7%C3%A3o%202019-08-28%20132230.png)

 ![image](https://github.com/anderson-raber/sfp_mikrotik/blob/master/Anota%C3%A7%C3%A3o%202019-08-28%20132251.png)
