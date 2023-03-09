# Spotify Web

Repo dell'esercizio `html-css-spotifyweb` del 07/03/2023

## Objective
Riprodurre fedelmente ed in maniera responsive la struttura della pagina che ci è stata fornita.

## Issues

1. Problema di dimensione dell'overlay della colonna dovuto ad una altezza aggiuntiva di 4px del container dell'immagine.

## Issues fixes

1. Le immagini, come è noto, hanno come modalità di display `inline-block`, questo mandava in tilt l'altezza del container che risultava di 4px maggiore rispetto all'altezza effettiva dell'immagine, ciò è dovuto alle proprietà intrinseche dell'inline-block. La soluzione è stata quella di impostare la modalità di display delle immagini in `display: block`, in questa maniera il contenitore rivela in maniera esatta l'altezza dell'immagine.


## References
[Dveloper Mozilla Aspect Ratio](https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio#try_it)

[W3Schools Link Tag](https://www.w3schools.com/tags/tag_link.asp)

[W3Schools Link Media Attributes](https://www.w3schools.com/tags/att_link_media.asp)

## What i learned

1. Ho imparato ad usare meglio ed in maniera più efficiente le Media Queries, scrivendo all'interno del link nell'head `media="screen and(x)"` che non vengono scaricate automaticamente dal sito (facendo risparmiare banda), anche grazie all'approfondimento fatto nel pomeriggio del 09/03/2023

## Conclusions

Sono rimasto molto sorpreso dalla velocità con la quale sono riuscito a stendere il codice e dei pochi problemi, che a differenza delle volte precedenti, ho riscontrato durante la scrittura. Nonostante sia un rogetto difficile mi è sembrato molto seplice, infatti ho pensato spesso di aver dimenticato di inserire alcune cose o di non aver fatto funzionare tutto perfettamente. Sono molto soddisfatto del risultato in quanto sono anche riuscito ad aggiungere alcune modifiche bonus al codice. Mi sento molto più veloce nel comprendere la struttura delle pagine e nel realizzarle al livello pratico. Sono molto soddisfatto dei miei progressi ed anche sempre più fiducioso delle mie capacità.