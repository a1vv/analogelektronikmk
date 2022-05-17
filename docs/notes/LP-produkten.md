---
aliases: 
- Loop-gain-poles product
- loop-gain pole product
dg-publish: True
tags: 
- analogelektronik
---
$\omega_{0}=^{n}\sqrt{LP_{n}}$ 
$LP_{n}=[1-A \beta(0)]p_{1}p_{2}...p_{n}$

där $\omega_{0}$ är [[Bandbredd|bandbredden]]!

[[Karakteristiska polynomet för matriser|Karakteristiska polynomet]] för [[system]] med två [[Slingpoler och Slingnollställen|slingpoler]] och inga [[Slingpoler och Slingnollställen|slingnollställen]] $(N(s)=1)$ är
$$P(s)-A \beta(0)B(s) =s^{2}-(p_{1}+p_{2})s+[1-A \beta(0)]p_{1}p_{2}]$$
Samma [[system]] med [[Poler|polerna]] i [[Butterworthposition]] har polynomet
$$P(s)-A \beta(0)N(s)=s^{2}-(p_{1}'+p_{2}')s+\omega_{0}^{2}$$
Identifiering ger 
$$\omega_{0}^{2}=\left|[1-A \beta(0)]p_{1}p_{2}\right|$$

# Hur man ökar LP-produkten
Om LP-produkten är för låg kan man inte nå önskad [[bandbredd]]. Då behöver man på något sätt öka LP-produkten, vilket kan göras på två olika sätt.

Varje [[förstärkande steg]] lägger till en faktor $\omega_{T}$ till LP-produkten. Man kan alltså öka LP-produkten genom att lägga till fler [[förstärkande steg]], eller genom att öka storleken på $\omega_{T}$. Det kan göras genom att öka [[Biasering|bias]]-current eller byta till en “bättre” [[transistor]].