---
aliases: 
- 
dg-home: True
dg-publish: True
tags: 
- moc
- analogelektronik
---
Kursen i Analog Elektronik handlar i stort sett om [[Systematisk Förstärkardesign]]. Den börjar med att lägga fram grunderna för [[förstärkare]] med hjälp av [[nullor]] ([[Tvåportsnätverk|tvåport]]). Därefter presenteras olika [[förstärkande steg]] som kan användas i [[flerstegsförstärkare]], samt hur dessa kopplas ihop för att få rätt polaritet när man ersätter [[Nullor|nullorn]] i sin modell med [[Transistor|transistorer]]. Man lär sig även räkna på [[Slingförstärkning|slingförstärkningen]], genom att byta ut [[Transistor|transistorerna]] mot dess hybrid-pi modeller. För att [[Förstärkare|förstärkaren]] ska fungera måste [[Transistor|transistorerna]] operera i sin [[arbetspunkt]], och måste därmed [[Biasering|biaseras]]. För att få önskad prestanda på sin [[förstärkare]] behöver man oftast [[Frekvenskompensering|frekvenskompensera]], därför läggs mycket tid på [[poler]], [[nollställen]] och [[Stabila och Instabila System|stabilitet]]. 

# Föreläsningar
```dataview
LIST FROM #föreläsning AND #analogelektronik SORT file.name DESC
```


# Laborationer
```dataview
LIST FROM #laboration AND #analogelektronik  SORT ASC
```


# Övning
```dataview
LIST FROM #övning AND #analogelektronik  SORT ASC
```


# Seminarium
```dataview
LIST FROM #seminarium AND #analogelektronik  SORT ASC
```


# Inlämningar
```dataview
LIST FROM #inlämning AND #analogelektronik  SORT ASC
```


# Kvistar
```dataview
table 
	dateformat(file.ctime,"MMM dd yyyy") as "Planted at",
	dateformat(file.mtime,"MMM dd yyyy") as "Last tended to",
	length(file.inlinks)+length(file.outlinks) as "In/Out Links"
FROM #analogelektronik  
sort length(file.inlinks)+length(file.outlinks) DESC
```