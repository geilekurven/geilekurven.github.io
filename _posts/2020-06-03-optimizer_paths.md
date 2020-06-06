---
layout: post
title:  "Die gehobene Kunst der Kritzelei"
date:   2020-06-03 12:30:00 +0200
math: true
---

Heute zeige ich euch, wie man auf äußerst elegante Art und Weise, Kunstwerke von 2 bis 3 jährigen Menschen imitiert. Hierzu trainieren wir ein Neuronales Netzwerk. Obwohl das jetzt richtig abgefahren klingt, ist das nichts anderes wie ein gutes Minimum einer speziellen Funktion \\(f: \mathbb{R}^n \rightarrow  \mathbb{R}\\) mit einer Optimierungsmethode zu finden. Doch wieder abgefahren ist aber, dass \\( n \\) oft größer \\(10^6\\) ist.   
Die Optimierungsmethode folgt also einem Pfad von einem Startpunkt zu einem Minimum auf einer circa \\(10^6\\) dimensionalen Funktion.
Kann man sich jetzt schwer vorstellen, aber stellt euch einfach einen Pfad in 3 Dimensionen vor und glaubt dabei ganz fest daran, dass es noch 999997 weitere Richtungen gibt. 
Nun projizieren wir den Pfad, auf die Länge jedes Schrittes und erhalten dabei die Winkel zwischen aufeinanderfolgenden Schritten.  
Als Ergebnis erhalten wir je nach Optimierungsmethode wunderschöne Krizeleien:
<p float="left">
<img src="/figures/ls.png" title="line search training" alt="line search training" width="350"/> 
<img src="/figures/sgd.png" title="Gradientenabstieg training" alt="Gradientenabstieg training" width="350"/> 
</p>
Pfade von Trainings eines Neuronalen Netzwerks mit einer Liniensuche (links) und mit Gradientenabstieg (rechts).

