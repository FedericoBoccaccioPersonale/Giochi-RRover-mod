# Giochi\RRover mod (Rescue Woody) 🎮 🇮🇹
https://federicoboccaccio.wordpress.com/rrover-mod/

Questa è una mod per Rescue Rover

# Importante
⚠️ I file "Source code (.zip)" e "Source code (.tar.gz)" sono generati automaticamente da GitHub.<br>
Contengono la versione leggermente modificata per poter funzionare online o sui sistemi case sensitive, come il Pinguino 🐧.<br>
Puoi tranquillamente scaricare dalla release o giocare on line.

# Download
[Ultima versione](https://github.com/FedericoBoccaccioPersonale/Giochi-Mini-collezione-JQ-2022/releases/latest) (tutte le piattaforme disponibili)

🌐 [Gioca on line](https://federicoboccacciopersonale.github.io/Giochi-Mini-collezione-JQ-2022/Mini%20collezione%20JQ%202022/public_html/index.html)

# Come renderlo giocabile online
1. Ho scaricato l' ultima release da https://github.com/caiiiycuk/js-dos<br>
Il sito di riferimento è js-dos.com
0. Ho caricato il progetto estratto dallo zip nel mio repository.
0. Ho estratto lo zip che contiene solo il gioco moddato in una cartella
0. In quella cartella creo una sottocartela `.jsdos`
0. Lì dentro ci va un file `dosbox.conf` che deve come minimo contenere l' autoexec di configurazione di dosbox.
0. Comprimi la cartella in zip, ma va rinominato in `R1MOD.jsdos`
0. Carica R1MOD.jsdos nella cartella della index
0. A questo punto ho dovuto modificare l' index di js-dos modificando i percorsi in quelli locali, nell' head, le righe *crossorigin*
0. Ho modificato `const props = Dos(document.getElementById("app"),` mettendo un url col percorso locale. Anche pathPrefix deve essere un percorso relativo, il percorso in cui cercare il file jsdox.

OK, funziona! 🎉🎉🎉

Adesso devo modificare il file per lanciare automaticamente il gioco.<br>
Al momento DosBox parte ma ha il supporto solo per il formato 8.3, anche se è impstata la versione 7.1. Quindi conviene rinominare le cartelle.

E adesso **è andato tutto a rotoli!** E questo dimostra che gitHub ha **clamorosamente** fallito, perchè secondo la leggenda in caso di disastro epico è possibile tornare a un commit funzionante precedente. Be', non è possibile.

~~Sono abbastanza sicuro che con un po' di impegno sia pssibile anche lanciare più giochi, se tutti compressi nello stesso file.~~

Dato che è impossibile ricreare l' evento fortuito di prima, o forse da attribuire a potenze demoniache, dal punto di vista scientifico sono tenuto a considerarlo un evento casuale irripetibile e a dichiarare DEL TUTTO IMPOSSIBILE eseguire un gioco DOS in github page.


**js-dos** è una libreria JavaScript che emula DOSBox nel browser. È pensata per essere facile da integrare in siti web e supporta sia giochi DOS che applicazioni Windows 9x. Ecco le sue caratteristiche principali, secondo Copilot:

- **Esecuzione in browser e Node.js**
- **Supporto a giochi pesanti**
- **Multiplayer e salvataggi cloud**
- **Compatibilità mobile**
- **Backend multipli**: DOSBox, DOSBox-X
- **Versioni in WebAssembly e JavaScript puro**

Solo che non funziona.



# Informazioni
Su GitHub c' è il repository principale, su GitLab è presente il suo clone per backup.
Puoi anche scaricare il gioco da Itch.