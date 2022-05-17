---
aliases: 
- pn-dioder
- pn-dioden
dg-publish: True
tags: 
- komponentfysik
- analogelektronik
---
Ett likriktat element som bara leder ström i ena riktningen. Består av två regioner, den ena är n-[[Dopning|dopad]] och den andra är p-[[Dopning|dopad]].
![[pn-diod.png]]
n-regionen har en högre [[potential]] än p-regionen. Elektronerna i [[Ledningsband|ledningsbandet]] vill röra sig från n till p, samtidigt som hålen vill röra sig från p till n. Båda rörelserna ger upphov till en ström som går från p till d genom dioden. 



## Utarmningskapacitans
mellan de två “plattorna” finns det en utarmningskapacitans, som är lika stor som den för en [[plattkondensator]] med avståndet $d_{tot}$ mellan plattorna.

### För [[storsignal]]:

$C=\frac{Q}{U}$

Laddningen ges av 
$Q=eN_{D}Ad_{n}$
där $Ad_{n}$ blir en volym

### För [[småsignal]]:
kollar vi på små förändringar av spänningen
$C_{j}=\frac{\delta Q}{\delta U_{a}}\approx \frac{dQ}{dU_{a}}$
![[Pasted image 20220510102853.png|300]]