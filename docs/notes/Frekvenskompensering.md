---
aliases: 
- frekvenskompenserar
- frekvenskompenseringen
- frekvenskompensera
- frekvenskompenserad
- frekvenskompenserade
tags: 
- analogelektronik
dg-publish: True
---
## Varför frekvenskompensera?
När man designar en [[förstärkare]] har man oftast några önskemål om dess funktion. Det kan vara att man vill att [[Förstärkning|förstärkningen]] ska vara lika stor för alla frekvenser, att frequency roll-off ska vara så skarp som möjligt, att [[Stegsvar|stegsvaret]] ska vara så snabbt som möjligt m.m. För att uppnå önskad prestanda behöver man oftast använda sig av frekvenskompensering.

## Vad innebär frekvenskompensering?
För att få önskad prestanda vill vi att [[Systempoler|systempolerna]] ska befinna sig på en specifik position. Positionen beror på vad det är vi vill uppnå. Om vi vill ha jämn [[förstärkning]] för alla frekvenser inom [[Bandbredd|bandbredden]] ([[Maximal Flat Frekvensgång|MFM]]) vill vi att [[Systempoler|systempolerna]] ska vara i [[Butterworthposition]]. Detta gör man med olika [[Frekvenskompenseringsmetoder]].

[[Hur frekvenskompensering kan påverka rotorten - MFM system]]



**question**{: #question .hash}  
 why do our amplifiers behave like filters? 

När man flyttar systempolerna förändras systemets karaktäristiska polynom **question**{: #question .hash}  
 vad är det
* frekvenskompensering tillämpas bara på [[Dominanta och Icke-dominanta poler|dominanta poler]]
* Idealt ska kompensering ej påverka [[LP-produkten]] eller $A \beta(0)$.