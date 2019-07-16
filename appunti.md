# VETTORI

#### SOMMA

Dati due vettori $\overrightarrow{v}=(x_1, y_1)$ e $\overrightarrow{w}=(x_2,y_2)$ la loro somma è un *vettore* avente per **componenti** la somma delle componenti di $v$ e $w$:

$\overrightarrow{v}+\overrightarrow{w}=(x_1+x_2, y_1+y_2)$ (regola del parallelogramma)

- Il **modulo** di $|\overrightarrow{v}+\overrightarrow{w}|\le  |\overrightarrow{v}|+|\overrightarrow{w}|$ 
- $|\overrightarrow{v}|=\sqrt{x^2+y^2+...}$ somma dei quadrati di ogni componente.

#### MOLTPIPLICAZIONE per uno *scalare*

Dati il vettore $\overrightarrow{v}=(x,y)$ ed il numero reale $\lambda$, il vettore $\lambda\overrightarrow{v}$ ha per componenti quelle del del vettore $\overrightarrow{v}$ moltiplicate per $\lambda$:

$\lambda\overrightarrow{v}=(\lambda x, \lambda y)$

Esempio: sia $\overrightarrow{v}=(1,2)$, determinare $2\overrightarrow{v}$ e $-\overrightarrow{v}$.

- $2\overrightarrow{v} = (2\times1,2\times2)=(2,4)$

- $-\overrightarrow{v} = (-1\times1,-1\times2)=(-1,-2)$

- $-\overrightarrow{v}$ è l'**opposto** di $\overrightarrow{v}$. Ovvero il **verso** si inverte perché moltiplicato per un numero **negativo**.


#### Prodotto scalare e angolo tra vettori

Dati due vettori $\overrightarrow{v}=(x_1, y_1)$ e $\overrightarrow{w}=(x_2,y_2)$ il loro **prodotto scalare**, che si indica con la notazione $\overrightarrow{v}\times\overrightarrow{w}$, è assegnato dalla seguente formula:

- $\overrightarrow{v}\times\overrightarrow{w}= x_1 \times x_2 + y_1 \times y_2$ che è **numero reale**
  - $x_1=|\overrightarrow{v}|\cos\Theta_1$
  - $x_2=|\overrightarrow{w}|\cos\Theta_2$
  - $y_1=|\overrightarrow{v}|\sin\Theta_1$
  - $y_2=|\overrightarrow{w}|\sin\Theta_1$

$\overrightarrow{v}\times\overrightarrow{w}= x_1 \times x_2 + y_1 \times y_2 = |\overrightarrow{v}|\cos\Theta_1 \times |\overrightarrow{w}|\cos\Theta_2+|\overrightarrow{v}|\sin\Theta_1 \times |\overrightarrow{w}|\sin\Theta_2$
$=|\overrightarrow{v}|\times|\overrightarrow{w}|\times(\cos\Theta_1\cos\Theta_2+\sin\Theta_1\sin\Theta_2)$
$=|\overrightarrow{v}|\times|\overrightarrow{w}|\times\cos(\Theta_2-\Theta_1) = |\overrightarrow{v}|\times|\overrightarrow{w}| \times\cos\alpha$

- $\Theta_1$ è l'angolo del vettore $\overrightarrow{v}$
- $\Theta_2$ è l'angolo del vettore $\overrightarrow{w}$


Segue che:
  - $\overrightarrow{v}\times\overrightarrow{w}> 0\iff \alpha$ è **minore** di 90°
  - $\overrightarrow{v}\times\overrightarrow{w}< 0\iff \alpha$ è **meggiore** di 90°
  - $\overrightarrow{v}\times\overrightarrow{w}= 0\iff \alpha$ **retto** (vettori **perpendicolari**) oppure uno dei due è il vettore **nullo**

**Angolo tra due vettori**

Per calcolare l'angolo tra due vettori si deve trovare l'angolo tra **ogni** vettore e l'asse delle $x$, dopo si fa la differenza tra gli angoli.
Angolo con l'asse delle $x$: $\Theta_{v_1}=\arcctg(\frac{j}{i})$

Esempio:
$\overrightarrow{v_1} = 15\overrightarrow{i} - 8\overrightarrow{j}$
$\overrightarrow{v_2} = 8\overrightarrow{i} - 15\overrightarrow{j}$


Angolo tra $v_1$ e $v_2$ con l'asse delle $x$:

$\Theta_{v_1}=\arcctg(\frac{-8}{15})$
$\Theta_{v_2}=\arcctg(\frac{-15}{8})$

Angolo tra $v_1$ e $v_2$: $\Theta_{v_1}-\Theta_{v_2}$

**NOTA**: $\frac{\pi}{2}$ è l'angolo di 90°.

#### Calcolo vettori

Dati due punti $A=(x,y)$ e $B=(x,y)$. Per determinare il **vettore** $\overrightarrow{r}_{AB}$ si fa la somma delle differenze dei componenti **arrivo - partenza**:

$\overrightarrow{r}_{AB} = (x_B-x_A)\overrightarrow{i} + (y_B-y_A)\overrightarrow{j}$


#### DIFFERENZA

Somma della differenza tra le componenti. Esempio:

Siano dati:
$\overrightarrow{a} = 0\overrightarrow{i}-3\overrightarrow{j}$
$\overrightarrow{b} = 4\overrightarrow{i}+0\overrightarrow{j}$

La loro differenza:
$\overrightarrow{a}-\overrightarrow{b} = (0-4)\overrightarrow{i}+(-3+0)\overrightarrow{j} = -4\overrightarrow{i}-3\overrightarrow{j}$


\pagebreak

#ELETTROMAGNETISMO

## CARICHE

Corrente Elettrica è la carica totale che passa per un filo in un periodo di tempo.

Per la **legge della conservazione** della carica il voltaggio totale erogato dal sistema è uguale alla somma di tutti i cali del circuito.??

**Conservazione dell'energia**

Con resistenze maggiori si ha un calo maggiore di voltaggio (del potenziale)
Con resistenze minori si ha un calo minore

#### GENERATORE

Un generatore di tensione, è caratterizzato da una **differenza di potenziale** ai suoi capi denominata **forza elettromotrice** e si tratta di una tensione elettrica misurata in $V$ (volt).

Il generatore di tensione, sarà in grado di erogare una corrente $I$ solo una volta che il circuito sarà chiuso su di un carico (resistenza) $R$. 
Se il generatore rimane flottante **non** vi sarà alcuna corrente circolante.

- $f.e.m.$ in $V$ (volt): forze elettro-motrici (*tensioni* ai capi dei **generatori**)
- $c.d.t.$ in $V$ (volt): cadute di tensione (*tensioni* ai capi delle **resistenze**)

**TENSIONE** = $d.d.p.$ differenza di potenziale (elettrico)

#### CONDENSATORE

Ha la capacità di immagazzinare energia elettrica tra le sue armature

- **Circuito (interruttore) aperto** $\rArr$ **non passa corrente**
- **Circuito (interruttore) chiuso** $\rArr$ **passa corrente**

- **Condensatore scarico** + **circuito chiuso** (interruttore chiuso, quindi passa corrente) $\rArr$ passa corrente attraverso il Condensatore **finché** esso non sarà **carico**.
- **Condensatore carico** $\rArr$ **non passa** corrente (si comporta come un circuito aperto)

#### INDUTTORE

è il **duale** del Condensatore.

**Corto circuito** $=$ **Circuito chiuso** $\rArr$ **resistenza prossima allo 0** quindi passa corrente.

**STAZIONAREITÀ**:

- **Condensatore** $\rArr$ 
- **Induttore** $\rArr$ **corto circuito** / **circuito chiuso**

**NON STAZIONAREITÀ**:

- **Condensatore** $\rArr$ 
- **Induttore** $\rArr$ **generatore di corrente**
