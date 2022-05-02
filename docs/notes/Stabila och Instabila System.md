---
tags: 
- systemochtransformer
- analogelektronik
aliases: 
- stabilt
- instabilt
- stabila systemet
- stabilt system
- stabila system
- instabila system
- stabilt system
- instabilt system
- stabilitet
- stabil
- ostabil
dg-publish: True
---
[[System]] brukar kallas **instabila** om en liten förändring av insignalerna leda till ett obegränsat växande av [[Tillståndsvariabler|tillståndsvariablerna]]. Är ett [[system]] stabilt å andra sidan så svänger det in sig snabbt. Tänk en pendel, det finns ett fall där den hänger rakt ned, och ett annat fall när den pekar rakt upp. När den hänger rakt ned är det ett stabilt [[system]], för om man puttar lite på pendeln kommer den svänga in sig själv till samma position. Om den pekar rakt upp däremot behöver man bara peta på den för att den ska falla ned, och aldrig återgå till samma position.

> För stabila [[system]] går den homogena lösningen mot noll då $t \rightarrow\infty$ 

En rationell fuktion H(s) är överföringen till ett stabilt [[system]] då 
* Antalet [[Poler|poler]] ≥ antalet [[Nollställen|nollställen]]
* Alla [[Poler|poler]] ligger i vänstra halvplanet
![[stabiltellerinstabilt.png]]
På vänster sida AVTAR den exponentiella komponenten (det är ett [[Laplace-planet|laplace-plan]]), medan den ökar på höger vilket ger upphov till instabilitet!! 


# Stabilitet för [[Differentialekvationer|differentialekvationen]] $\vec{x}'=A \vec{x}+\vec{f(t)}$

$\sigma(A)$ defineras som $max_{1\leq k\leq n}(Re(\lambda_{k}))$ och används för att se om en [[Differentialekvationer|differentialekvation]] är stabil eller inte. Det finns tre fall:
## Homogen [[Differentialekvationer|differentialekvation]]
1. $\sigma(A)<0$, dvs alla [[egenvärden]] är negativa $\Rightarrow$ **stabil**
2. $\sigma(A)=0$, dvs alla [[egenvärden]] är negativa eller noll $\Rightarrow$ **[[neutralt stabil]]** eller **instabil**
3. $\sigma(A)>0$, dvs alla [[egenvärden]] är positiva $\Rightarrow$ **instabil**

## Homogen [[Differentialekvationer|differentialekvation]] med [[Diagonalisering|diagonaliserbar]] [[matris]] A
1. $\sigma(A)<0$, dvs alla [[egenvärden]] är negativa $\Rightarrow$ **stabil**
2. $\sigma(A)=0$, dvs alla [[egenvärden]] är negativa eller noll $\Rightarrow$ **[[neutralt stabil]]** 
3. $\sigma(A)>0$, dvs alla [[egenvärden]] är positiva $\Rightarrow$ **instabil**

## [[Inhomogena Differentialekvationer|Inhomogen Differentialekvation]]
tolkas som ett [[system]] där insignalen är $\vec{f(t)}$ och utsignalen är $\vec{x}'$.
1. $\sigma(A)<0$, dvs alla [[egenvärden]] är negativa $\Rightarrow$ **[[insignal stabil]]**
2. $\sigma(A)=0$, dvs alla [[egenvärden]] är negativa eller noll $\Rightarrow$ **icke [[insignal stabil]]** 
3. $\sigma(A)>0$, dvs alla [[egenvärden]] är positiva $\Rightarrow$ **icke [[insignal stabil]]**

# Stabil
alla lösningar $\vec{x(t)}\rightarrow \vec{0}$

# Instabil
det finns någon lösning som är obegränsad! 

[[Neutralt Stabil]]
[[Insignal Stabil]]
[[Insignal-utsignalstabilt]]