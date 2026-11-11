# Directory repository GitHub (Forrom58)

- **Repository**: `Forrom58.github.io` (pubblica), file `index.html` nella radice.
- **Indirizzo pagina**: https://forrom58.github.io
- **Funzionamento**: legge l'elenco delle repository pubbliche con l'API GitHub
  (`api.github.com/users/Forrom58/repos`), in ordine alfabetico. Le nuove repository compaiono da sole.
- **Per ogni repository**: solo nome e descrizione. Il nome è un link all'app
  (GitHub Pages o indirizzo "Website"); se l'app non c'è, porta al codice.
- La repository `Forrom58.github.io` (la pagina stessa) è esclusa dall'elenco.
- **Icone**: 40 px a sinistra del nome, lette in automatico dal `manifest.json` di ogni app
  (icona più vicina a 96 px, "any"); in mancanza, da apple-touch-icon / icon della pagina.
- **Nomi**: maiuscola all'inizio e dopo ogni trattino (es. Lettore-Daisy, Diritti).
  Eccezioni nell'oggetto `NOMI` dello script (es. `"cuocipasta": "CuociPasta"`).
- **Descrizioni**: si modificano su GitHub (rotellina accanto ad "About" → Description).
- **Limiti**: solo repository pubbliche; l'API senza login consente 60 letture/ora per rete.
- **Stile**: sfondo scuro, testi tenui, niente giallo. Versione sulla riga del titolo, a destra (`v1.3`).
- **Per modifiche**: cambiare `UTENTE` nello script o i colori in `:root`; aggiornare il numero di versione.
