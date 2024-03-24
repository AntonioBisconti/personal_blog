+++
title = 'Sessione Aprile #3'
date = 2024-03-18T14:09:16+01:00
draft = false
tags = ["università", "Fisica", "Metodi Matematici"]
author = "Antonio Bisconti"
description = """
Riassunto degli ultimi giorni di studio 12/03-24/03
"""
+++
## Altro cambio di luogo (Definitivo)
In questi giorni ho studiato alla biblioteca che si trova a villa  [Trabia](https://turismo.comune.palermo.it/palermo-welcome-luogo-dettaglio.php?tp=68&det=22&id=272). Davvero un bel posto, non solo 
per l'edificio in sé, ma per tutto il verde che c'é attorno. 
Una delle cose piú belle é farsi una breve passeggiata nel parco fra una sessione di studio e l'altra.
Nei prossimi giorni l'idea é quella di studiare lí la mattina e il resto del pomeriggio a casa, giusto per 
spezzare la giornata.

## Argomenti Studiati 
In questi giorni ho superato abbondantemente la metà del programma; i macro argomenti studiati sono:
- **Polinomi Ortogonali**
- **Teoria integrazione di Lebesgue**
- **Cenni Analisi Complessa**
- **Operatori Lineari**
- **Trasformata di Furie e Laplace**
- **Distribuzioni**

I polinomi ortogonali sono un argomento che non mi é piaciuto particolarmente.
Piú che altro perché possono essere definiti in tanti modi differenti e questo mi crea abbastanza confusione.
Molti tipi di polinomi ortogonali possono essere ricavati dalla _Formula di Rodriguez_
$$
F_n(x)=\frac{1}{w(x)}\frac{d^n}{dx^n}(w(x)Q(x)^n)
$$
A seconda di che tipo di funzioni sono $w(x)$ o $Q(x)$ si ottengono diversi risultati.

La teoria dell'integrazione di Lebesgue, invece, l'ho trovata particolarmente interessante. Generalizza l'integrale di Riemann,
inoltre dá una definizione di integrale che permette di fare molte piú cose rispetto a quella di Riemann (come passaggi al limite sotto il segno di integrale):
$$
\int_{\cal{D},[L]} f(x)dx = \sum_{i=0}^{\infty} y_i \mu(D_i)
$$
Analisi complessa penso sia stato l'argomento che ho preferito fra tutti, anche se non é proprio il topic principale del corso, ma ci servono soltanto 
dei risultati per fare alcuni tipi di conti. 
Uno dei più bei risultati dell'analisi complessa è sicuramente il _Teorema dei residui_
$$
\oint_{\gamma} f(z) dz = 2\pi i \sum_{k=0}^n\{f(z),z=z_k\}
$$
dove $f(z)$ è una funzione olomorfa in un regione $\mathcal{R}$ di $\Complex$ e $\gamma$ è una 
curva chiusa che circonda $n$ singolarità della funzione $f(z)$. Questo teorema permette di calcolare degli 
integrali in $\Reals$. 
Interessante anche la nozione di operatore, che si puó vedere come una mappa fra spazi di Hilbert
$$
\hat{O}: \cal{H_1} \longrightarrow \cal{H_2}
$$
Tutta la teoria che si costruisce su questo argomento é di fondamentale importanza per la meccanica quantistica,
basta pensare all'operatore momento $\hat{p}=-i\hbar \frac{\partial}{\partial x}$
Non ho molto da dire sulla teoria della trasformata di furie, definita in questo modo:
$$
\hat{f}(p)=\frac{1}{\sqrt{2\pi}}\int_\Reals e^{-ipx}f(x)dx
$$
ho incontrato parecchie difficoltà nel capire come la trasformata sia definibile per funzioni $f(x) \in \mathcal{L^2}(\Reals)$
Abbastanza neutro sono anche sulla trasformata di Laplace:
$$
F(z)=\int_0^\infty e^{-zt}f(t) \ dt
$$
Non né ho ben capito l'utilità pratica al momento (se non quella che nei prossimi giorni mi devo spaccarmi di esercizi 
su queste trasformate perché escono sempre all'esame)
La teoria delle distribuzioni mi é sembrata (per il momento) un teoria costruita ad hoc per dare un senso ad oggetti 
come la delta di dirac $\delta$
$$
\delta \coloneqq \int_\Reals \delta(x-x_0)f(x) \ dx = f(x_0)
$$
Per definire questo oggetto bisogna introdurre il concetto di distribuzione:
Si definisce distribuzione un funzionale continuo sull'insieme $\mathcal{D}(\Reals)$
Dove $$\mathcal{D}(\Reals)= (f(x) \in C^\infty(\Reals) \ \text{a supporto compatto su} \ \Reals)$$
Su tutti questi argomenti mi devo ancora esercitare seriamente, li ho soltanto visti da un punto di vista teorico. 
L'esercizio però é fondamentale visto che l'esame, oltre che un orale, prevede uno scritto...



## Sensazioni durante lo studio 
Ho la sensazione di essere sempre non abbastanza per questo corso di studi, mi spiego meglio: gli argomenti quando li studio li capisco,
però il tempo che ci impiego mi sembra tanto. Per esempio una lezione di due ore di metodi ci posso impiegare anche tre ore per studiarla a casa. 
Certo, poi dopo questo tempo, almeno da un punto di vista di teoria, gli argomenti li ho abbastanza chiari, ma poi bisogna anche fare esercizi e lí passa altro tempo giustamente.
La cosa ideale per me sarebbe capire tutto durante la lezione in classe e poi tornato mettersi direttamente a fare esercizi. 
Questo renderebbe la preparazione dell'esame molto più veloce.
La questione é: sono io?, é l'università in generale?, é la facoltà?
Francamente non lo so, non ho una risposta a questo. 
Queste riflessioni forse però meritano un post dedicato.
Nonostante io mi sia fatto un programma di studio per preparare questo esame, la sensazione di essere indietro rimane. 
Penso che queste siano in generale delle sensazioni condivise anche 
da altri mie colleghi. Le cose che sto studiando sono sicuramente molto interessanti ed eleganti,
ma certamente, finito questo esame, non penso di andarle ad approfondire piú di tanto; per il momento penso questo,
possibilmente in futuro cambio idea. -11 giorni all'esame. 

