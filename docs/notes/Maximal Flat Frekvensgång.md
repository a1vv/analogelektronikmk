---
aliases: 
- butterworthsystem
- butterworth system
- maximum flat magnitude
- MFM
- MFM system
- MFM-system
tags: 
- analogelektronik
dg-publish: True
---
Ett vanligt önskemål är att [[Förstärkning|förstärkningen]] skall vara lika för alla frekvenser hos [[Signal|signalen]]. Detta stämmer när [[Systempoler|systempolerna]] ligger i [[Butterworthposition]]

$$A \beta(s)=A \beta(0) \frac{1}{1+\frac{s}{(\omega_{0})^{n}}}$$
alla [[poler]] ges av $1+(\frac{s}{\omega_{0}})^{n}=0$ , skriv om s på [[polär form]] - alla [[poler]] kommer ligga på en halvcirkel i vänster halvplan, där radien är lika med [[Bandbredd|bandbredden]]. Vinkeln mellan alla [[poler]] ges av $\theta=\frac{k\pi}{n}$. För att [[System|systemet]] ska bli [[Stabila och Instabila System|stabilt]] behöver man ibland flytta [[Poler|polerna]] längs cirkelns omkrets så att [[System|systemet]] blir [[Stabila och Instabila System|stabilt]]. Det görs via [[Frekvenskompensering]]

[[Hur frekvenskompensering kan påverka rotorten - MFM system]]

By converting our [[system]] to a butterworthsystem we can find the ideal [[Systempoler|system poles]] (if we want maximum flat magnitude)

If our [[system]] is a second order [[system]]:
$$p_{1,2}'=-\frac{\omega_{0}}{\sqrt{2}}(1\pm j) \Rightarrow \sum\limits p'=-\sqrt{2}\omega_{0}$$
![[2nd order mfm system.png|350]]
(ska stå 45 grader)
If our [[system]] is a third order [[system]]:
$$\begin{cases} p_{1}'= -\omega_{0}   \\ p_{2,3}'=-\omega_{0}\left( \frac{1}{2}\pm j\frac{\sqrt{3}}{2} \right)
\end{cases}\space\space\space \Rightarrow \sum\limits p'=-2\omega_{0}
$$
![[3rd order mfm system.png]]
(här är det 60 grader 🤡)