## Estrazione-Testi-Genius
Questo progetto permette di scaricare i testi delle canzoni partecipanti al Festival di Sanremo utilizzando Python e l'API di Genius. È stato sviluppato come parte di un corso di Coding Avanzato.

# Descrizione
Il progetto si propone di estrarre i testi delle canzoni di Sanremo da Genius. Inizialmente, sono state importate librerie fondamentali come Requests, BeautifulSoup, Selenium e JSON, per lavorare da remoto sulla pagina web del festival. Dopo aver valutato diverse fonti, abbiamo scelto Genius per la sua struttura HTML costante.

Il codice principale include funzioni per recuperare i titoli, gli autori e i testi delle canzoni. Abbiamo implementato una serie di funzioni che:

Estraendo i link delle canzoni da una pagina specifica del festival.
Recuperando i titoli e gli autori da ogni link.
Scaricando i testi delle canzoni e salvandoli in un database SQLite.

# Funzionalità
Estrazione automatica dei testi delle canzoni di Sanremo.
Possibilità di cercare canzoni specifiche per anno.
Salvataggio dei testi in file JSON e in un database SQLite.
Generazione di una tag cloud delle parole più frequenti nei testi estratti.

# Tecnologie Utilizzate
Linguaggio di programmazione: Python
Librerie:
Requests
BeautifulSoup
Selenium
SQLite3
JSON
Database: SQLite

# Installazione

git clone https://github.com/tuo-username/estrazione-testi-sanremo.git

cd estrazione-testi-sanremo

pip install -r requirements.txt

# Contributi

I contributi sono benvenuti! Se desideri migliorare il progetto o aggiungere funzionalità, sentiti libero di inviare una pull request o aprire un problema.


