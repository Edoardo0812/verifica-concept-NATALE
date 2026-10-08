NATALE Edoardo Maria, Studente ITS Accademia Nautica dell'Adriatico iscritto al secondo anno di progettazione navale, Copilot
# ANOMALIE

| Codice o foglio | Dove (riga o cella) | Valore letto nel foglio | Problema | Controllo fatto da me |
|---|---|---|---|---|
| CS-03 | Riga CS-03, colonna L (m) | 2400.0 | Valore di lunghezza fuori scala rispetto alle altre imbarcazioni (2400 m anziché un valore paragonabile a 24 m) | Confronto diretto tra le lunghezze del foglio (da 16.0 m a 24.0 m) |
| CS-04 | Riga CS-04, colonna Dislocamento (t) | 8500 | Valore di dislocamento anomalo e fuori scala per un battello da addestramento | Confronto diretto con gli altri dislocamenti del foglio (da 48 t a 90 t) |
| CS-02b | Riga CS-02b, colonne Dislocamento (t) e Allievi | Dislocamento: 620 / Allievi: 60 | Valori sproporzionati rispetto alla scheda duplicata CS-02 (62 t e 6 allievi) | Confronto diretto tra la riga CS-02 e la riga CS-02b |
| CS-05 | Riga CS-05, colonna T (m) | 4.90 | Immersione sproporzionata rispetto alla lunghezza (16.0 m) | Confronto diretto con le altre immersioni del foglio (da 1.40 m a 1.80 m) |
| CS-06 | Riga CS-06, colonna B (m) | NaN (vuota) | Dato della larghezza mancante | Lettura della cella vuota e della nota "Larghezza non misurata" |
| CS-06 | Riga CS-06, colonna Velocità (kn) | dodici | Valore espresso in formato testo alfabetico anziché numerico | Lettura del valore della cella rispetto alle altre righe numeriche |
| CS-07 | Riga CS-07, colonna Equipaggio | 0 | Incongruenza tra il valore 0 nella colonna ed il testo nella nota | Confronto tra la cella Equipaggio (0) e la nota ("Equipaggio: due marinai in turno") |
| Pesi_CS01 | Riga 10, colonna Unità della riga | t (1.2) | Unità di misura espressa in tonnellate anziché in kg come il resto della tabella | Rilevazione dell'unità "t" rispetto alle altre righe in "kg" |
| Pesi_CS01 | Riga 11, colonna Massa | 70000 | Il totale dichiarato è errato ed è un valore testo inserito a mano, non una formula | Somma in Excel eseguita da me: 42000+12000+9000+3500+1800+2500+2200-500+(1.2*1000) = 73700 kg (differenza di 3700 kg) |
| Pesi_CS01 / Concept | Riga CS-01 (Concept) vs Pesi_CS01 | Concept: 85 t / Pesi_CS01: 73.7 t | Il dislocamento di 85 t nel foglio Concept non corrisponde alla somma reale dei pesi di CS-01 (73.7 t) | Confronto da me calcolato: 85 t (Concept) - 73.7 t (Somma Pesi_CS01) = 11.3 t di discrepanza |
| Registro | Riga 2, colonna Data | 13/13/2026 | Data non valida (il mese 13 non esiste) | Verifica del formato data |
