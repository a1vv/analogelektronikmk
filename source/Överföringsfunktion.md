---
aliases: [överföringsfunktionen, överföringsfunktioner, transfer function, transfer functionsa]
tags: [analogelektronik,]
dg-publish: true
---
För ett [[Linjära och Tidsinvarianta System|linjärt tidsinvariant system]] $S$ gäller
$$e^{st}\xrightarrow{S}H(s)e^{st}$$
där överföringsfunktionen ges av$$H(s)=\int_{-\infty}^{\infty}e^{-st}h(t)dt=\mathcal{L}(h(t))(s)$$
där integralen kan tolkas som [[Laplacetransformationer|laplacetransformen]] av $h(t)$.


Antag att $S$ är [[Linjära och Tidsinvarianta System|LTI]] och reellt (dvs [[Impulssvar|impulssvaret]] är reellt). Då är 
1. $S(sin(wt))=A(w)sin(wt+\varphi(w))$
2. $S(cos(wt))=A(w)cos(wt+\varphi(w))$


## [[Differentialekvationer]]
Om man har en funktion som 
$$y'''+3y'+y=2w''+w$$
blir överföringsfunktionen
$$H(s)=\frac{2s^{2}+1}{s^{3}+3s+1}$$
dvs insignal genom utsignal.


## [[Poler]] och [[nollställen]]
Generellt kan en överföringsfunktion skrivas på formen
![[överföringsfunktion.png]]
$n_{1}$, $n_{2}$ osv kallas [[nollställen]] och $p_1$, $p_2$ osv kallas [[poler]].
[[Poler|Polerna]] och nollställena kan markeras i [[Laplace-planet|s-planet]]. [[Poler]] markeras med x och [[nollställen]] med o.
![[polerochnollställenisplanet.png]]
Förekommer endast i par, och är då konjugat till varandra.

Placeringen av [[Singularitet|singulariteterna]] i överföringsfunktionen avgör exempelvis om ett [[system]] är [[Stabila och Instabila System|stabilt]] eller inte.

> Alla [[poler]] till överföringsfunktionen är [[egenvärden]] till systemmatrisen och altså egensvängningsfrekvenser till [[System|systemet]]. Om $s=p$ är en [[Poler|pol]] till $H(s)$ så finns en fri svängning till [[System|systemet]] med tidsberoende av formen $e^{pt}$.


## Se också
[[Samband mellan impulssvar och överföringsfunktion]]
[[Amplitudfunktionen|amplitudfunktion]]
[[Frekvensfunktion]]
[[Fasfunktionen|fasfunktion]]



