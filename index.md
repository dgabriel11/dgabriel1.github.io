# Implementarea relatiilor in Markdown

## Implementarea relatiilor /legaturilor catre alte fisiere (gazduite pe alte servere)

Fisierele accesate prin link-uri pot fi:
1. Gazduite pe alte servere (de ex: accesarea unui alt site)
2. Gazduite pe server-ul site-ului curent.

De asemenea, prin aceste link-uri se pot accesa si sectiuni din pagina curenta sau sectiuni din alte pagini ale aceluiasi site.


### Sintaxa unui link Markdown

Tiprui de link-uri in Markdown:
1. Link-uri clasice (normale)
2. Link-uri referentiate

#### Link-urile clasice:

<b>Variante:</b>
[Textul link-ului](https://google.com "accesare site google")  

#### Link-urile referentiale:

Iata un [link][link1] catre site-ul google:

[link1]: https://google.com

Varianta prescurtata a link-urile referentiale:

Iata un link [important] catre site-ul google:


[important]: https://google.com
