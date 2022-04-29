
# Performance Matters - Serverside optimization

Een deeltaak waarin je drie server-side performance optimalisaties toepast op jouw project.

## Context

Deze leertaak hoort bij sprint 10 Performance Matters. Dit is een deeltaak die je individueel uitvoert.

In het college S10W1-02-server-side-performance wordt behandeld hoe je server-side optimalisatie kan toepassen.



## Doel van deze opdracht

Je hebt geleerd dat *Performance* een heel belangrijk aandachtspunt is bij het bouwen van websites. In deze opdracht leer je in een paar stappen laag hangend performance fruit te pakken. Met een aantal relatief simpele ingrepen kan je jouw website performance verbeteren. 

Het resultaat is gegarandeerd het sneller inladen van jouw website!

## Werkwijze

Opdracht: Implementeer vier serverside performance optimalisaties: Minifying, Code splitting, Caching en Compressie.


Deze opdracht gaat over de [bouw](#bouwen) fase van de DLC.



### Bouwen

Voor deze opdracht voer je vier performance optimalisaties uit op een bestaand project. Kies een bestaand project uit jouw Github account om de optimalisaties op uit te voeren. Begin met een [Performance Audit](https://github.com/fdnd-task/performance-matters-performance-audit)


<details>
<summary>Aanpak</summary>

1. Minify jouw CSS door gebruik te maken van PostCSS (optioneel: minify ook je client-side javascript).
2. Pas handmatig code-splitting toe op client-side javascript bestanden zodat alleen zaken worden ingeladen die écht gebruikt worden.
3. Verstuur cache-control headers bij GET requests naar jouw website, kies beargumenteerd een max-age.
4. Pas compressie toe. (optioneel: kies de juiste compressie aan de hand van het request)

#### Materiaal bouwfase

- [How to minify CSS with Node.js @ benborgers.com](https://benborgers.com/posts/node-minify-css)
- [Code splitting @ MDN](https://developer.mozilla.org/en-US/docs/Glossary/Code_splitting)
- [Cache headers in Express js app @ Regbrain.com](https://regbrain.com/article/cache-headers-express-js)
- [Gzip compression with Node.js @ victorvr.com](https://www.victorvr.com/tutorial/compresion-gzip-con-nodejs)
- [Node.js compression middleware @ expressjs.com](http://expressjs.com/en/resources/middleware/compression.html)
- [Compression @ npmjs.com](https://www.npmjs.com/package/compression)

</details>



## Criteria

Focus sprint 10 - De focus van deze sprint ligt op het beter en sneller laten werken van een applicatie.

### Deze leertaak hoort bij het gedragscriterium:

M: Je combineert aangeboden principes en conventies op het gebied van frontend, interface design en vormgeving.
C: Je kan ontwerpkeuzes, eigen ideeën en producten begrijpelijk overbrengen aan belanghebbenden.

### Deze opdracht is done als:

- [ ] Je hebt de vier performance optimalisaties geïmplementeerd
- [ ] Je hebt de performance optimalisatie geanalyseerd met een [Performance Audit](https://github.com/fdnd-task/performance-matters-performance-audit) vooraf én achteraf.
- [ ] Je hebt de performance optimalisatie gedocumenteerd in de Readme van de leertaak.

