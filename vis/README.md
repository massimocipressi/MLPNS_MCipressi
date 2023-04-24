Il seguente grafico è stato fatto da me, usando Matlab, per la presentazione che ho portato all'esame di Modellazione e simulazione numerica. Mostra l'andamento del valore del numero di riproduzione R(t) durante l'epidemia di COVID 19 in Italia. Sono rappresentati i dati comunicati ufficialmente, a confronto con quelli calcolati da me utilizzando un semplice modello SIR, a cui sono stati forniti i dati sui positivi di giorno in giorno. Il risultato dipende dai parametri del modello, in particolare, è nota un'incertezza sul valore del tempo di riproduzione, che porta ad un'incertezza sul calcolo di R(t).

![image](https://github.com/massimocipressi/MLPNS_MCipressi/blob/main/vis/R_easy.jpg)

Il problema principale di questo grafico è che il margine d'incertezza è riportato mostrando le curve superiore e inferiore. Per non creare eccessiva distrazione, queste sono di un verde chiaro, ma così diventano difficilmente leggibili. Meglio rappresentare l'errore con un'area in trasparenza, questo permette anche di metterlo nella legenda con una label sola.
Sono state poi ingrandite le scritte e cambiati i limiti degli assi. Nel primo grafico questi eliminano certe parti poco credibili, questo aiuta la visualizzazione delle parti più importanti, ma potrebbe essere considerato disonesto, qui, quindi, i limiti sono settati per vedere tutto.

![image](https://github.com/massimocipressi/MLPNS_MCipressi/blob/main/vis/vis.png)

Nota: il dato ufficiale veniva calcolato con una simulazione Monte Carlo che usa Metropolis e avevo effettuato anche questo calcolo per quell'esame, trovando risultati migliori.
