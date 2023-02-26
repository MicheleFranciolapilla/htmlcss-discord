#　HOME PAGE DISCORD (Seconda parte: completamento layout)

**L'obiettivo dell'esercizio era quello di riprodurre la schermata del sito Discord, il cui layout di soli blocchi era stato implementato nel precedente esercizio.**

---

**Soluzioni adottate:**

- *La pagina si presenta organizzata in blocchi (header, sezioni, footer) di altezza uguale o prossima (utilizzo di `height` e `min-height` riferiti ad una variabile dichiarata nel foglio di stile.*
- *Il layout della pagina, inoltre, presenta una regolare organizzazione in senso verticale di elementi centrati e di ampiezza fissa, anch'essa riferita ad una variabile dichiarata nel foglio di stile.*
- *Tutti i colori sono conformi alla pagina originale del sito ed il font utilizzato e' il Google font Rubik Semibold 600.*
- *Si e' fatto uso del link a "font awesome" per le icone dei vari social media.*
- *La parte **bonus** dell'esercizio prevedeva l'inserimento di immagini "svg" con profilo di curve, all'interno della pagina. Detti elementi sono stati inseriti tra le sezioni e "colorati" utilizzando l'attributo `filter` di css, inoltre, una di esse e' stata ribaltata per esigenze di layout utilizzando l'attributo css `transform: scale(-1).*
- *Si e' fatto uso dei selettori avanzati `:nthchild(4n+3)` per poter selezionare i blocchi cui attribuire caratteristiche non standard, "driblando" gli elementi "wave" presenti tra le sezioni.*
- *Si sono utilizzate variabili, all'interno del foglio di stile, relativamente ad alcuni colori e parametri dimensionali dei blocchi.*
- *In tutte le aree del lavoro si e' fatto ricorso ai blocchi flexbox; in particolare, nel footer si sono utilizzati blocchi flexbox annidati.*




