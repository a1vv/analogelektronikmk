---
aliases: [amplifier, förstärkaren,]
tags: [analogelektronik,]
dg-publish: true
---
En förstärkare ökar effektinnehållet i en [[Signal]].  En förstärkare FÖRSTÄRKER en [[Signal]] utan att ändra dess form.

$$ v_{in} = A \cdot v_{ut}$$

Allmänt: 
$$A_t = \frac{Q_L}{Q_g}$$
där $Q_L$ (Quantity Load) är utsignalen, $Q_g$ (quantity generator) är insignalen och A är [[Förstärkning|förstärkningen]]. Om A är negativ inverteras [[Signal|signalen]] (*inverterande förstärkare*). Ofta är en av noderna i både ut och inången kopplade till en gemensam jord. jorden agerar som en emensam “return path” för [[Signal]]-spänningarna.

En förstärkare kan vara en sortomvandlare (omvandlar ex ström till spänning).

Open loop amplifier : utan [[Feedback]]
Closed loop amplifier : med [[Feedback]]

Käll- och laststorheterna behöver ej vara lika
- Spänningsförstärkare V-V
- Transadmittansförstärkare V-I
- Transimpedansförstärkare I-V
- Strömförstärkare I-I
![[förstärkare.png]]

## Blacks modell
![[blacks modell.png]]

## Superpositionsmodellen
bygger på blacks modell
![[superpositionsmodellen.png]]
$$A_t = A_{tinf} \frac{-AB}{1-AB}+ \frac{A_{t0}}{1-AB} = A_{tinf} \frac{-AB}{1-AB}$$

V=RI
V/I=R
I/V=S

## Se också
[[Förstärkning]]
[[Nullor]]
[[OP-förstärkare]]
[[Flerstegsförstärkare]]