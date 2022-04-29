---
tags: [analogelektronik]
dg-publish: true
---
Linjärisering av den [[Bipolär transistor|bipolära transistorns]] överföringsdiagram ger en modell med linjära element. Linjära modeller är enkla att räkna på men gäller bara i ett begränsat område kring linjäriseringspunkten - vi kallar detta [[småsignal]]! Kollektorströmmen ([[storsignal]]) ges av
$$
I_{C}=I_{S}e^{\frac{V_{BE}}{V_{T}}}\left(\frac{1+V_{CE}}{V_{A}}\right) \space ,\space V_{BE}>0 \space and \space V_{BC}<0
$$
Med [[taylorutveckling]] kan man få fram ett uttryck för totalsignalen $i_C$ runt [[Arbetspunkt|arbetspunkten]] $Q$
$$
i_{C}=I_{C}+i_{c}=f(V_{BE})+f'(V_{BE})\cdot v_{be}+\sum\limits_{n=2}^{\infty} \frac{1}{n!} \frac{\delta^{n}f(V_{BE})}{\delta v^{n}_{BE}} = BIAS+Gain\cdot signal+distortion
$$
hybrid $pi$-modellen är likadan för både PNP och NPN och ser ut som i bilden nedan. Kondensatorerna brukar försummas.
![[hybrid-pi-modellen-bjt.png|450]]
där konstanterna ges av 
![[hybrid-pi-bjt-rpi-ro-gm.png|450]]
man kan härleda ekvationerna ovan från den exponentiella grafen typ, och utifrån ekvationerna kan man sedan resonera sig fram till kretsschemat ovan. Man vet att $I_{C}$ ska gå från Collector till Emittor. $V_{T}$ är ca 25mV i rumstemperatur

### Modellens parametrar 
Genom att beräkna derivatorna i [[Arbetspunkt|arbetspunkten]] får man uttryck på modellens parametrar.
$$\frac{i_{c}}{i_{b}}=\beta_f$$
där $\beta_f$ står i transistorns datablad “common emitter current gain”