NATALE Edoardo Maria, Studente ITS Accademia Nautica dell'Adriatico iscritto al secondo anno di progettazione navale, Copilot
Marco, [Tua Classe], Copilot

# RELAZIONE SUL CONTROLLO DELLA SCHEDA CONCEPT

## Che cosa contiene il foglio
Il foglio di calcolo didattico analizzato è composto da tre fogli principali:
1. **Concept**: elenca i dati generali di 8 schede di battelli da addestramento (lunghezza, larghezza, immersione, dislocamento, velocità, equipaggio, allievi e zona).
2. **Pesi_CS01**: riporta il dettaglio dei gruppi di peso relativi alla sola imbarcazione CS-01, esplicitando la massa e l'unità di misura per ciascuna voce.
3. **Registro**: raccoglie le annotazioni cronologiche dell'ufficio didattico relative alle verifiche effettuate sulle schede.

---

## Quale scheda si può usare come base del corso, e quali no
Sulla base dei controlli incrociati e delle verifche effettuate sui dati numerici:

- **Schede utilizzabili come base del corso**:
  - **CS-01 (Aurora)** e **CS-02 (Nereo)** possono essere prese in considerazione come base didattica, poiché presentano parametri di lunghezza, larghezza, immersione e dislocamento coerenti con la tipologia di battello da addestramento costiero. Tuttavia, per la scheda CS-01 occorre tenere conto della discrepanza emersa tra il dislocamento dichiarato nella scheda principale (85 t) e la somma reale ricalcolata nel foglio dei pesi (73.7 t).
  
- **Schede NON utilizzabili**:
  - **CS-03 (Libeccio)**: presenta una lunghezza palesemente errata e fuori scala ($2400.0\text{ m}$).
  - **CS-04 (Grecale)**: riporta un dislocamento anomalo ed esagerato ($8500\text{ t}$).
  - **CS-02b (Nereo - copia)**: presenta valori di dislocamento ($620\text{ t}$) e di allievi ($60$) del tutto sproporzionati rispetto alla versione CS-02 originale.
  - **CS-05 (Maestrale)**: ha un'immersione ($4.90\text{ m}$) non proporzionata rispetto alla lunghezza dell'imbarcazione ($16.0\text{ m}$).
  - **CS-06 (Scirocco)**: manca del dato della larghezza ed esprime la velocità in formato alfabetico ("dodici").
  - **CS-07 (Tramontana)**: mostra una contraddizione tra il valore nullo dell'equipaggio ($0$) e la nota che specifica la presenza di due marinai in turno.

---

## Limiti
L'agente IA ha evidenziato diverse anomalie formali e numeriche, ma non è stato possibile verificare l'origine dei refusi o determinare con certezza i valori corretti da attribuire alle imbarcazioni. Il foglio non contiene:
- Le metodologie di misurazione o i rilievi originali per confermare le dimensioni reali.
- Dati relativi alle linee d'acqua, ai coefficienti di forma o alla carena per valutare l'immersione reale.
- Formule matematiche dinamiche (il totale del foglio pesi è un valore di testo inserito manualmente).
- Informazioni o norme navali esterne (come richiesto dalle direttive della prova).

 Pertanto, i valori errati o mancanti sono stati definiti semplicemente come "non presente" o non coerenti, senza effettuare integrazioni a intuito.

---

## Strumento
Per svolgere l'attività è stato utilizzato l'assistente IA Copilot.

*Esempio di frase o proposta dell'agente modificata/scartata durante la revisione:*
L'agente aveva inizialmente calcolato la somma del foglio `Pesi_CS01` sommando direttamente i valori numerici della colonna massa senza considerare la diversa unità di misura della riga "Dotazioni di sicurezza" ($1.2\text{ t}$). Ho corretto l'output dell'agente convertendo manualmente $1.2\text{ t}$ in $1200\text{ kg}$ ed eseguendo la somma algebrica corretta ($73.700\text{ kg}$ anziché $70.000\text{ kg}$ o $70.001,2\text{ kg}$).
