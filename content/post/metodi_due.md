+++
title = 'Sessione Aprile #2'
date = 2024-03-12T22:55:27+01:00
draft = false
tags = ["università", "Fisica", "Metodi Matematici"]
author = "Antonio Bisconti"
description = """
Riassunto secondo giorno di studio di Metodi Matematici, poteva andare peggio
"""
+++



## Cambiare Luogo ogni tanto fa bene
Oggi sono andato a studiare alla biblioteca regionale, si trova in pieno centro storico a palermo.
All'interno ci sono degli spazi molto ampi e lo stile é complessivamente abbastanza classico.
L'unico problema é che spesso ci sono sempre dei lavori di ristrutturazione, a volte viene 
sacrificata la facciata oppure i locali interni. Allego uno fato delle sala lettura principale che per 
me merita molto.
![Sala lettura Biblioteca Regionale Sicilia, Palermo](https://www.regione.sicilia.it/sites/default/files/2023-06/sala%20lettura%20biblioteca%20centrale%20regione%20siciliana_2__.jpg)
Purtroppo questa sala oggi era chiusa per lavori in corso.
Avrei potuto studiare a casa, ma visto che per queste tre settimane 
non andrò a lezione ho voluto cambiare aria, giusto per separare, almeno per la mattina,
il luogo di studio con quello di riposo. Molto probabilmente nei giorni successivi studierò 
sempre a casa, però almeno per questi primi giorni preferisco fare in questo modo.

## Cosa ho fatto
Di mattina ho studiato 4 ore. I due argomenti principali sono stati:
1. Serie di Furie 
2. Convoluzione

Se considero lo spazio di hilbert: 
$$
\cal{L}(-\pi, \pi)=\{ f(x), \  \text{L-misurabili} \ : \int_{-\pi}^{\pi} \ |f(x)|^2 < \infty \} 
$$
e l'insieme totale fatto da funzioni ortonormali 
$$
\mathscr{F}=\left(\phi_o=\frac{1}{\sqrt{2\pi}},\dots, \ \phi_{2l-1}= \frac{1}{\sqrt{\pi}}\sin{lx},  \ \phi_{2l}= \frac{1}{\sqrt{\pi}}\cos{lx}, \ l \in \N \right) 
$$
una funzione $f \in \cal{H}$ che appartiene allo spazio di hilbert la posso scrivere, sfruttando il teorema visto in [Sessione aprile #1](https://antoniobisconti.blog/post/organizzazione_esami/), come: 
$$
f= \frac{P_0}{2} + \sum_{l=1}^{\infty} (P_l\cos(lx)+ D_l\sin(lx))
$$
dove:
$$
\begin{align*}
    P_0&= \frac{1}{\pi}\int_{-\pi}^{\pi} f(x) \\
    P_l&= \frac{1}{\pi}\int_{-\pi}^{\pi} \cos(lx)f(x)dx\\
    D_l&= \frac{1}{\pi}\int_{-\pi}^{\pi} \sin(lx)f(x)dx 
\end{align*}
$$
Dati due segnali $f, g \in \cal{L}^2(\R)$ si definisce prodotto di convoluzione:
$$
(f*g)(x)=\int_{\R} f(\tau)g(x-\tau)d\tau
$$ 
Il prodotto di convoluzione é:
- Commutativo
- Associativo
- Distributivo rispetto alla somma

Ma la cosa piú importante, per cui é utile, é che prese due funzione ne restituisce una che ha le caratteristiche migliori di entrambe.
Se la $f$ é derivabile, ma la $g$ no, la convoluzione restituisce una funzione che é derivabile.
il pomeriggio non ho studiato nulla, mi sono riposato.

## Fine giornata abbastanza creativa
La giornata é finita tentando di creare un video stile _Vlog_ con capcut, programma di editing gratuito disponibile anche per desktop.
Mi sono reso conto, provando in prima persona, quanto lavoro ci sia dietro anche un semplice video parlato con qualche scritta, musica e taglio dei momenti morti.
Non so se farò mai dei video su youtube, ma nel dubbio ci ho provato. L'idea sarebbe sempre quella di raccontare le proprie giornate di studio 
attraverso dei video.

## Programmi per domani
Domani l'idea sarebbe di fare i polinomi ortogonali, argomento che durante il corso non mi é piaciuto particolarmente.

