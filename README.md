# ArduWin
Un <b>framework</b> grafico per <u>Arduino</u> designato per schermi lcd I2C

Contiene una organizzazione simile a quelle dei maggiori framework grafici per computer (ad esempio Qt o wxWidgets)

Permette di designare interfaccie dinamiche sfruttando le classi c++. <br>
Ogni interfaccia e' composta da Controlli (<b>GControl</b>), come ad esempio Etichette (<b>GLabel</b>) o pulsanti (GButton). Essi vengono aggiunti all' interno delle finestre (<b>GWindow</b>) che contengono anche altri campi/proprietà come il titolo, un pulsante predefinito
per andare indietro, un nome, e metodi per gestire i controlli contenuti.

Tutte le finestre si possono gestire attraverso delle raccolte (<b>GWinList</b>), che permettono di organizzarle, gestirne
la visualizzazione e l'allocazione in memoria.

Il tutto e' pensato per gestire anche gli eventi all' interno della interfaccia (es pressione di un pulsante GButton) tramite 
gestori che ricevono un <b>GEvent</b>.

All' interno del framework e' inoltre possibile gestire gli errori, tramite <b>GError</b>, che permette di ottenere informazioni 
sull' errore e ottenerne alcune caratteristiche.

Il tutto e' completamente open source. <br>
<b><u>Ulteriori informazioni su come iniziare ad usarla sono contenute nel file per-iniziare-arduwin.pdf</b></u>
