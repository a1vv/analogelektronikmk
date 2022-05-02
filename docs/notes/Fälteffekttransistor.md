---
aliases: 
- mosfet
- fet
- fieldeffecttransistor
tags: 
- komponentfysik
- analogelektronik
dg-publish: True
---
Metal Oxide Semiconductor Field Effect [[Transistor]]
![[nMOS fälteffekttransistor.png]]
$V_{GS}$ måste vara högre än tröskelspänningen $V_{TH}$ för att det ska gå en ström $I_{DS}$ genom [[Transistor|transistorn]].
![[mos.png]]
en [[nMOSFET|nMOS]] [[transistor]] har en [[Dopning|p-typ]] [[halvledare]]. Det finns alltså en jävla massa hål, men varje hål kommer från en acceptor - som har en proton mindre och alltså ger upphov till negativa laddningar. När man lägger på en spänning på gaten repelleras hålen, vilket skapar ett negativt laddat område - **[[Utarmningsområdet|utarmningsområde]]** ([[Utarmningsområdet|depletion region]]) som är tömt på rörliga laddningar. De få elektroner som finns kommer hopas i [[utarmningsområdet]], och dess laddning ges av $Q_{n}=C_{ox}(U_{GS}-U_{TH})$.
![[MOStransistor.png]]
När man lägger på en spänning $V_{DS}$ får man elektronerna i [[utarmningsområdet]] att röra sig, vilket skapar strömmen $I_{DS}$! [[Strömtäthet|Strömtätheten]] för kanalen av elektroner ges av 
$$J=en \frac{\mu}{n}\mathcal{E}$$
det elektriska fältet ges av
$$\mathcal{E}=\frac{U_{DS}}{L_{g}}$$
vilket ger 
$$J=\frac{Zh}{L_{g}}en \mu_{n}U_{DS}$$
där $L_{g}$ är längden på kanalen, $Z$ är dess bredd, $h$ dess tjocklek och $n$ är koncentrationen. Om man ökar $U_{GS}$ kommer koncentrationen av elektroner att öka, vilket ökar [[Strömtäthet|strömtätheten]] (ledningsförmågan).

Tröskelspänning - koncentrationen av elektroner i [[utarmningsområdet]] är lika hög som koncentrationen av acceptorer. 


Source och Drain n-dopas så att det finns gott om elektroner. Följande [[Banddiagram]] kan ritas upp
![[mosfet-banddiagram.png]]
där Gate-spänningen indikeras av det gråa rätblocket. Energinivån på elektronerna kan ses som en vattennivå, och transistorns olika lägen kan beskrivas av hur vattnet flödar. 

## Strypd mod
![[mosfet strypt.png]]
$$V_{GS} < V_t$$ Strömmen kan inte ta sig från source till drain.

![[Pasted image 20220117140430.png]]
$$V_{GS}>V_t$$
Genom att öka gatespänningen över tröskelspänningen kan en ström börja gå från source till drain
## Mättnadsområdet
Mättnadsområdet kan lätt förstås med vattenanalogen
![[Pasted image 20220117140633.png]]
oavsett hur mycket man ökar drain-spänningen kommer det inte påverka hur mycket ström som flödar från source till drain.
$$V_{DS} > V_t - V_{GS}$$
$I_d$ oberoende av $V_{GS}$

## Linjära området
![[linjärt område mosfet.png]]
$$V_{DS} > V_t - V_{GS}$$
$I_d$ beror av $V_{DS}$ . Strömmen ökar med drainspänningen i det linjära området.

[[nMOSFET]]
[[pMOSFET]]