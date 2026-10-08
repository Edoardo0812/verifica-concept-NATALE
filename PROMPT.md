NATALE Edoardo Maria, Studente ITS Accademia Nautica dell'Adriatico iscritto al secondo anno di progettazione navale, Copilot
# PROMPT UTILIZZATI E REVISIONI

## Prompt 1: Analisi del foglio Concept

**Prompt incollato:**
> "Sono uno studente ITS e devo effettuare il controllo dati di una scheda concept didattica. Nel foglio 'Concept' è presente una tabella con i dati tecnici di 8 imbarcazioni da addestramento (lunghezza, larghezza, immersione, dislocamento, velocità, equipaggio, allievi, zona). Forniscimi l'output esclusivamente sotto forma di tabella elencando le anomalie riscontrate. Non applicare norme navali, non calcolare stabilità e non inventare o cercare sul web numeri o dati non presenti nel foglio."

- **Che cosa ha risposto l'agente:** L'agente ha generato una tabella con le principali anomalie del foglio Concept (CS-03, CS-04, CS-02b, CS-05, CS-06, CS-07).
- **Che cosa ho tenuto:** Ho tenuto tutte le segnalazioni di incongruenza e di dati mancanti/in formato errato evidenziate dall'agente.
- **Che cosa ho scartato o corretto, e perché:** Ho scartato l'ipotesi di correggere a intuito i valori numerici nel foglio originale e ho eseguito personalmente il confronto riga per riga per verificare l'effettiva presenza di ciascun valore prima di inserirlo nel report.

---

## Prompt 2: Analisi dei gruppi di peso (Pesi_CS01)

**Prompt incollato:**
> "Sono uno studente ITS e sto controllando la scheda dei pesi della nave CS-01 Aurora. Nel foglio 'Pesi_CS01' è presente una tabella con la riga di ogni gruppo di peso, la massa, l'unità della riga e le note. Analizza le righe e forniscimi una tabella con le discrepanze o anomalie riscontrate. Non applicare norme di stabilità, non cercare dati sul web e non aggiungere cifre o unità non presenti nel foglio."

- **Che cosa ha risposto l'agente:** L'agente ha segnalato l'unità in tonnellate alla riga delle dotazioni di sicurezza, la zavorra mobile negativa e la nota sul totale dichiarato.
- **Che cosa ho tenuto:** Ho tenuto la segnalazione della riga espressa in tonnellate e l'indicazione che il totale non era calcolato tramite formula.
- **Che cosa ho scartato o corretto, e perché:** Ho scartato la somma fornita dall'agente in quanto aveva sommato direttamente i valori senza effettuare la conversione d'unità della riga in tonnellate. Ho eseguito io stesso il calcolo manuale (convertendo $1.2\text{ t}$ in $1200\text{ kg}$) ottenendo la somma corretta di $73.700\text{ kg}$ ($73.7\text{ t}$) e riscontrando la discrepanza sia con il totale dichiarato ($70.000\text{ kg}$) che con il dislocamento della scheda Concept ($85\text{ t}$).
