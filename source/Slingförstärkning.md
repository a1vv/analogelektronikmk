---
aliases: [slingförstärkningen, loop gain, loop-gain]
tags: [analogelektronik]
dg-publish: true
---
$$
\begin{cases}
Q_{o}=AQ_{e}\\Q_e'=\beta Q_o
\end{cases}
\Rightarrow
Q_{e}'=A\beta Q_{e}
$$
$A\beta$ kallas slingförstärkning, och är [[Förstärkning|förstärkningen]] genom hela slingan (tänk dig en slinga som går genom [[Förstärkare|förstärkaren]] och feedbacknätverket, en sluten loop). [[Negativ återkoppling]] strävar efter att minimera $Q_e$. $A\beta$ är negativ vid [[negativ återkoppling]]!! (också enhetslös). A är [[förstärkning]] och $\beta$ är [[Feedback]].

Slingförstärkningen beskriver [[Förstärkning|förstärkningen]] i [[Feedback|feedback-nätverket]] (årerkopplingsslingan). Det är produkten $A\beta$ som är relevant, inte A och $\beta$ för sig. 

> $A \beta$ är [[frekvensberoende]], och borde egentligen skrivas $A\beta(s)$, där $s=j\omega$ är [[Laplace Transform Variable]].

$$A \beta(s)=A \beta(0) \cdot \frac{1}{1- \frac{s}{p_{1}}}\cdot\frac{1}{1- \frac{s}{p_{2}}}$$ 


### Beräkning av $A\beta$
![[Pasted image 20220207132042.png]]
För A: Ta bort [[Feedback|återkopplingen]], testgenerator som $Q_i$, teckna överföringen tll $Q_c$
För $\beta$: Nollställ $Q_g$, testgenerator som $Q_{c}$, teckna överföringen till $Q_i$. 
![[signalförstärkningsexempel.png]]
