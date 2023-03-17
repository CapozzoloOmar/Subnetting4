# Subnetting4

In questo esercizio abbiamo suddiviso una rete in **4 sottoreti**.
Per suddividerle tramite ip e far capire al router dove mandare i messaggi dobbiamo dividere gli indirizzi ip, perciò dividiamo 256 a 4 .
Otteniamo così **64**.
Dopo aver ottenuto questo numero sappiamo da quale indirizzo ip partono e finiscono tutte e 4 le sottoreti.
**0-63/64-127/128-191/192-255**
- 0-63 -->sottorete 1
- 64-127 -->sottorete 2
- 128-191 -->sottorete 3
- 192-255 -->sottorete 4
Dobbiamo fare attenzione però a non dare alle entrate del router o ai pc collegati i numeri iniziali e finali perchè **quelli iniziali rappresentano l'identificativo della rete** e i **finali rappresentano il broadcast**.
Fatto tutto ciò assegneremo gli ip e i gateway a ogni dispositivo e l'esercizio sarà finito
