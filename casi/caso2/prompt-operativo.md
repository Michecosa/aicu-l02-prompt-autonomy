# Prompt operativo

```txt
Migliora l’UX della dashboard ticket del progetto esistente in questa cartella

Obiettivi:
- Rendi la pagina più moderna, pulita e leggibile.
- Aggiungi filtri utili e una ricerca: stato, priorità e testo libero su titolo/descrizione.
- Inserisci indicatori rapidi per:
  - ticket totali,
  - ticket aperti,
  - ticket in lavorazione,
  - ticket chiusi.
- Migliora la gestione delle azioni:
  - pulsanti chiari per “Vedi”, “Modifica”, “Elimina”,
  - conferma eliminazione,
  - possibile spaziatura e iconografia coerente.
- Mantieni la paginazione server-side esistente.
- Risolvi eventuali problemi UX: usabilità su desktop e mobile, chiarezza dei badge stato/priorità, layout compatto e moderno.
```


# Prova di controllo
1. La lista dei ticket deve aggiornarsi mostrando solo i risultati pertinenti in base ai filtri impostati.
2. Il totale degli indicatori rapidi (*aperti + in lavorazione + chiusi*) deve corrispondere esattamente al contatore dei "ticket totali" e al numero effettivo di elementi presenti nel database.
3. Al momento dell'eliminazione di un ticket, deve apparire un popup o un messaggio di conferma. Se data la conferma, il ticket deve sparire e la lista deve aggiornarsi immediatamente
4. In modalità mobile, la tabella e i filtri non devono strabordare dallo schermo. Il menu dei filtri e i pulsanti d'azione devono rimanere facilmente cliccabili 