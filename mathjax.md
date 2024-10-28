<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


![Text descriptiv al imaginii](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954)

[homepage](index.md)

<h1>Inserarea ecuatiilor si formulelor MarthJax</h1>

<b>Sintaxa</b>

Formulele `MathJax` sunt inserate in aceeasi linie daca sunt plasate intr-o pereche de simboluri `$`

<i>Exemplu: Aceasta este o ecuatie: $a=bc$</i>

Formulele `Latex` (prin `MathJax`) se introduc pe rand nou intre doua perechi de simboluri $.

Exemplu:

$$a=b^c$$

<h1>RIDICAREA LA PUTERE (superscript)</h1>

Se foloseste meta-caracterul `Latex`: `^`

Exemplu:

$$a=10^7$$

<h1>`Subscript`</h1>

Se foloseste meta-caracterul `_`

<i>Exemplu:</i>

$$a_i = b^c$$


<h1>Gruparea Elementelor Din Formule</h1>

Elementele din formule se grupeaza prin Meta-caracterul `{`si`}`

$$ 10^{10} $$

<h1>Litere Grecesti</h1>

<i>Exemplu:</i>

`\alpha` -alpha litera mica $\alpha$


`\Alpha` -alpha litera Mare $\Alpha$

$$\beta$$

$$\Beta$$

<h1>Parantezele</h1>
- Parantezele rotunde se scriu direct (nu au un inteles special)
- Parantezele patrate se scriu direct (nu au inteles special)
- Acoladele, deoarece ele sunt meta-caractere de grupare, vor fi renderizate corect daca sunt `escapate` de intelesul lor special

Exemple:

$$a=(b+c)^{3x} - [3+6x]$$


<h1>Fractiile</h1>

<i>Exemplu:</i>

`\frac{numarator}{numitor}`

$$a=\frac{(a+bc)}{(d-c)}$$

<h1>Semnele de multiplicare si diviziune</h1>

<i>Exemple:</i>

$$a=c+10\times x$$

$$a=c+10\cdot x$$

$$a=b\div c$$

<h1>Suma</h1>

<i>Exemplu:</i>

$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$


<h1>Integrale</h1>

<i>Exemple:</i>

$$\int_0^1 x^4 dx$$
