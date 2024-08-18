

Per avere la conferma di essere nella cartella /home/mario/ è utile eseguire il comando pwd, il quale stamperà a schermo il percorso corrente. Digitare il seguente comando:

pwd
Gestione di file e directory

* pwd
Il comando pwd serve per mostrare la directory in cui ci si trova.

* ls
Il comando ls serve per elencare il contenuto di una directory.

La sintassi del comando è:  ls [opzione] [directory]

![alt text](../Images/Opzioni_ls.JPG)

* cd

Il comando cd serve per spostarsi all'interno delle directory del filesystem.

La sintassi del comando è:  cd [directory]

Spostarsi alla directory superiore<br>
cd ..<br>
Spostarsi da qualsiasi punto nella propria directory home:<br>
cd<br>
Spostarsi nella directory /etc:<br>
cd /etc

* mkdir

Il comando mkdir serve per creare directory all'interno del filesystem.

La sintassi del comando è: mmkdir [opzioni] directory

Creare la directory prova/ all'interno della directory corrente:<br>
mkdir prova

Creare la directory prova all'interno della propria home directory, qualunque sia la directory in cui ci si trova al momento:<br>
mkdir ~/prova

* cp

Il comando cp serve per:

copiare un file in un altro file;<br>
copiare un file in un'altra directory;<br>
copiare più file in un'altra directory;<br>
copiare directory.<br>
La sintassi del comando è la seguente:

cp [opzioni] origine destinazione

Copiare il file miofile della directory prova nella directory /prova1:<br>
cp /prova/miofile /prova1

Copiare il file miofile della directory /prova nella directory /prova1 dandogli il nome nuovofile:<br>
cp /prova/miofile /prova1/nuovofile

Copiare la cartella /prova, e tutto il suo contenuto, nella cartella /prova_copia:<br>
cp -r /prova /prova_copia

## mv

Sintassi<br>
$ mv [opzione] [origine] [destinazione]

Il comando mv di Linux ha due funzioni importanti. 

 1) In primo luogo, viene utilizzato per spostare i file da una directory a un’altra, ma può anche essere usato per spostare le directory stesse. 
 
 2) Una seconda possibile funzione del comando è quella di rinominare dati o cartelle. 

  Ci sono due modi possibili per farlo:

  1)  richiamare prima la directory di origine con il comando cd di Linux e spostate il file da lì a una directory di destinazione 

  $ mv clienti.txt ~/documenti/contatti/


  2)  memorizzate la directory di origine nel comando stesso ed eseguire il trasferimento da un’altra directory di lavoro.

  $ mv /home/fatture/clienti.txt /documenti/contatti/

  Esistono tre opzioni per mv:

 * -i o –interactive: questa opzione fa sì che il sistema chieda se un file o una directory devono essere sovrascritti.
* -u o –update: con questa opzione un file di origine viene spostato solo se quello di destinazione è più vecchio.
* -v o –verbose: questa opzione mostra il progresso durante lo spostamento.

Esempi di comando mv:

* mv *.txt /documenti/  sposta tutti i file .txt

* $ mv clienti.txt clienti_nuovi.txt rinomina il file

* $ mv fatture fatture_vecchie rinomina la cartella

* $ mv /fatture_vecchie /archivio  sposta la directory fatture_vecchie nella directory archivio


* rm e rmdir

Il comando rm serve per cancellare file o directory dal file system.

La sintassi del comando è: rm [opzioni] file ...
Alcune opzioni da utilizzare con il comando rm:

-i, chiede conferma prima di cancellare<br>
-f, forza la cancellazione del file senza chiedere conferma


Il comando rmdir serve per cancellare directory dal file system.

La sintassi del comando è: rmdir directory

Cancellare il file miofile:<br>
rm miofile

Cancellare la directory prova/ e tutto il suo contenuto:<br>
rm -rf prova/

Cancellare la directory prova/ solo se questa non contiene alcun file all'interno:<br>
rmdir prova/



Bibliografia:<br>
[Wiki_Ubuntu](https://wiki.ubuntu-it.org/AmministrazioneSistema/ComandiBase)<br>
[Permessi_File](https://wiki.ubuntu-it.org/AmministrazioneSistema/PermessiFile#chmod)