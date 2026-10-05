<!-- ELUCENIA technical documentation · peso-ideal-e-ajustado · it · no clinical/professional/rights approval -->

# Peso ideale e peso aggiustato

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/peso-ideal-e-ajustado)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Sesso

`sexo`

- `F` — Femminile
- `M` — Maschile

### Altezza

`altura`

cm · intervallo: 120–230

### Peso reale (per il peso corretto)

`peso`

kg · facoltativo · intervallo: 25–350

## Edizione del metodo

Devine 1974/Robinson 1983/Miller 1983; revisione Pai–Paloucek 2000; fattore locale 0,4 per peso corretto

## Formula documentata

Peso ideale (Devine): uomini 50 kg + 2,3 kg per pollice oltre 5 piedi; donne 45,5 kg + 2,3 kg per pollice oltre 5 piedi. In centimetri: 50 (45,5) + 2,3 × (altezza − 152,4) ÷ 2,54.

Peso corretto = Peso ideale + 0,4 × (peso reale − Peso ideale).

## Limiti e popolazione

Il peso ideale è una stima delle tabelle altezza/peso, non una misura della massa magra. La relazione farmacocinetica varia secondo il farmaco; questo abstract non conferma un fattore di aggiustamento universale di 0,4. La scelta del peso per il dosaggio deve seguire la fonte del farmaco e la popolazione corrispondente.

## Riferimenti

- [Pai MP, Paloucek FP. The origin of the "ideal" body weight equations. Ann Pharmacother, 2000.](https://doi.org/10.1345/aph.19381)

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
