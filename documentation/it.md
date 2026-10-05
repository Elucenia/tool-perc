<!-- ELUCENIA technical documentation · perc · it · no clinical/professional/rights approval -->

# Criteri PERC

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/perc)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Età ≥ 50 anni

`idade`

### Frequenza cardiaca ≥ 100 bpm

`fc`

### Saturazione di O₂ \< 95% in aria ambiente

`sat`

### Edema unilaterale dell’arto inferiore

`edema`

### Emottisi

`hemoptise`

### Intervento o trauma con ricovero nelle ultime 4 settimane

`cirurgia`

### TVP o EP pregressa

`tev`

### Uso di estrogeni (contraccezione o terapia ormonale sostitutiva)

`hormonio`

## Edizione del metodo

PERC/Kline 2004: 8 criteri negativi con sospetto iniziale basso; nessuna decisione automatica

## Formula documentata

Otto domande sì/no. PERC è negativo solo se tutte sono “no”. Usare solo se il medico ritiene già la bassa probabilità clinica (gestalt \< 15%).

## Limiti e popolazione

La PERC 2004 è stata derivata in pazienti di pronto soccorso valutati per embolia polmonare e testata in gruppi a rischio basso e molto basso. Gli otto criteri devono essere tutti negativi contemporaneamente, inclusi età \< 50 anni, polso \< 100/min e saturazione \> 94% nello studio originale. La regola non stabilisce un rischio nullo e la sua applicabilità dipende dalla selezione preventiva della popolazione; definizioni temporali e criteri di inclusione devono essere verificati nella versione utilizzata.

## Riferimenti

- [Kline JA et al. Clinical criteria to prevent unnecessary diagnostic testing in emergency department patients with suspected pulmonary embolism. J Thromb Haemost, 2004.](https://doi.org/10.1111/j.1538-7836.2004.00790.x)

- [Freund Y et al. Effect of the Pulmonary Embolism Rule-Out Criteria on subsequent thromboembolic events among low-risk emergency department patients: the PROPER randomized clinical trial. JAMA, 2018.](https://doi.org/10.1001/jama.2017.21904)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
