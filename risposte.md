{\rtf1\ansi\ansicpg1252\cocoartf2867
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue-Bold;\f1\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab560
\pard\pardeftab560\pardirnatural\partightenfactor0

\f0\b\fs40 \cf0 # Soluzioni - Logica e Algebra\
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0

\f1\b0\fs26 \cf0 \
## Domanda 1\
\
**Quanti sono i sottogruppi di $\\mathbb\{Z\}_3 \\times \\mathbb\{Z\}_7$?**\
\
**Opzioni:** 2, 4, 6, 8\
\
**Risposta corretta:** 4\
\
### Ragionamento\
\
1. $\\mathbb\{Z\}_3$ ha ordine 3 e $\\mathbb\{Z\}_7$ ha ordine 7.\
\
2. Poich\'e9 $\\gcd(3, 7) = 1$ (sono coprimi) si ha:\
   $$\\mathbb\{Z\}_3 \\times \\mathbb\{Z\}_7 \\cong \\mathbb\{Z\}_\{21\}$$\
\
3. $\\mathbb\{Z\}_\{21\}$ \'e8 un **gruppo ciclico** di ordine 21.\
\
4. I sottogruppi di un gruppo ciclico di ordine $n$ sono in corrispondenza biunivoca con i **divisori di $n$**. Per ogni divisore $d$ di $n$, esiste un unico sottogruppo di ordine $d$.\
\
5. I divisori di 21 sono: $1, 3, 7, 21$\
\
6. Quindi esistono esattamente **4 sottogruppi**.\
\
---\
\
## Domanda 2\
\
**Quale dei seguenti gruppi NON \'e8 ciclico?**\
\
**Opzioni:** $\\mathbb\{Z\}_2 \\times \\mathbb\{Z\}_3$, $\\mathbb\{Z\}$, $\\mathbb\{Z\}_2 \\times \\mathbb\{Z\}_4$, $\\mathbb\{Z\}_2 \\times \\mathbb\{Z\}_5 \\times \\mathbb\{Z\}_7$\
\
**Risposta corretta:** $\\mathbb\{Z\}_2 \\times \\mathbb\{Z\}_4$\
\
### Ragionamento\
\
Analizziamo ciascuna opzione applicando il teorema: il prodotto diretto $\\mathbb\{Z\}_m \\times \\mathbb\{Z\}_n$ \'e8 ciclico se e solo se $\\gcd(m, n) = 1$.\
\
1. **$\\mathbb\{Z\}_2 \\times \\mathbb\{Z\}_3$:** $\\gcd(2, 3) = 1$ \uc0\u8594  \'e8 ciclico ($\\cong \\mathbb\{Z\}_6$)\
\
2. **$\\mathbb\{Z\}$:** \'c8 ciclico per definizione, generato da $1$ (o $-1$)\
\
3. **$\\mathbb\{Z\}_2 \\times \\mathbb\{Z\}_5 \\times \\mathbb\{Z\}_7$:** Gli ordini sono coprimi a coppie:\
   - $\\gcd(2, 5) = 1$\
   - $\\gcd(2, 7) = 1$\
   - $\\gcd(5, 7) = 1$\
   \
   Quindi \'e8 ciclico ($\\cong \\mathbb\{Z\}_\{70\}$)\
\
4. **$\\mathbb\{Z\}_2 \\times \\mathbb\{Z\}_4$:** $\\gcd(2, 4) = 2 \\neq 1$ \uc0\u8594  **NON \'e8 ciclico**\
\
La risposta corretta \'e8 $\\mathbb\{Z\}_2 \\times \\mathbb\{Z\}_4$.\
\
---\
\
## Domanda 3\
\
**Quanti elementi ha il sottogruppo di $\\mathbb\{Z\}_4 \\times \\mathbb\{Z\}_6$ generato da $(\\bar\{2\}, \\bar\{2\})$?**\
\
**Opzioni:** 2, 4, 6, 8\
\
**Risposta corretta:** 6\
\
### Ragionamento\
\
Nel prodotto diretto, l'**ordine di un elemento $(a, b)$** \'e8 il minimo comune multiplo degli ordini di $a$ e $b$ nei rispettivi gruppi:\
$$\\text\{ord\}(a, b) = \\text\{mcm\}(\\text\{ord\}(a), \\text\{ord\}(b))$$\
\
1. In $\\mathbb\{Z\}_4$: l'elemento $\\bar\{2\}$ ha ordine 2 (poich\'e9 $2 \\cdot 2 = 4 \\equiv 0 \\pmod\{4\}$)\
\
2. In $\\mathbb\{Z\}_6$: l'elemento $\\bar\{2\}$ ha ordine 3 (poich\'e9 $3 \\cdot 2 = 6 \\equiv 0 \\pmod\{6\}$)\
\
3. Quindi: $\\text\{ord\}(\\bar\{2\}, \\bar\{2\}) = \\text\{mcm\}(2, 3) = 6$\
\
**Verifica empirica** (calcolando i multipli di $(\\bar\{2\}, \\bar\{2\})$):\
\
| $k$ | $k \\cdot (\\bar\{2\}, \\bar\{2\})$ |\
|-----|------------------------------|\
| 1   | $(2, 2)$                     |\
| 2   | $(0, 4)$                     |\
| 3   | $(2, 0)$                     |\
| 4   | $(0, 2)$                     |\
| 5   | $(2, 4)$                     |\
| 6   | $(0, 0)$                     |\
\
Il sottogruppo generato ha esattamente **6 elementi**.\
\
---\
\
## Domanda 4\
\
**$|\\\{g \\in \\mathbb\{Z\}_3 \\times \\mathbb\{Z\}_5 : \\langle g \\rangle = \\mathbb\{Z\}_3 \\times \\mathbb\{Z\}_5\\\}| = ?$**\
\
*Ovvero: quanti generatori ha $\\mathbb\{Z\}_3 \\times \\mathbb\{Z\}_5$?*\
\
**Opzioni:** 0, 4, 8, 12\
\
**Risposta corretta:** 8\
\
### Ragionamento\
\
1. Poich\'e9 $\\gcd(3, 5) = 1$ abbiamo:\
   $$\\mathbb\{Z\}_3 \\times \\mathbb\{Z\}_5 \\cong \\mathbb\{Z\}_\{15\}$$\
\
2. Il gruppo $\\mathbb\{Z\}_\{15\}$ \'e8 **ciclico** di ordine 15.\
\
3. I **generatori** di un gruppo ciclico $\\mathbb\{Z\}_n$ sono esattamente gli elementi coprimi con $n$. Il loro numero \'e8 dato dalla **funzione di Eulero** $\\varphi(n)$.\
\
4. Calcoliamo $\\varphi(15)$:\
   $$\\varphi(15) = \\varphi(3 \\cdot 5) = \\varphi(3) \\cdot \\varphi(5) = (3-1) \\cdot (5-1) = 2 \\cdot 4 = 8$$\
\
Quindi $\\mathbb\{Z\}_3 \\times \\mathbb\{Z\}_5$ ha esattamente **8 generatori**.\
\
---\
\
## Domanda 5\
\
**Chi \'e8 l'inverso di $1 + x$ nel campo $\\mathbb\{F\}_3[x]/\\langle 1 + x + 2x^2 \\rangle$?**\
\
**Opzioni:** $1 + x$, $1 + 2x$, $2 + x$, $2 + 2x$\
\
**Risposta corretta:** $2 + 2x$\
\
### Ragionamento\
\
Dobbiamo trovare un polinomio $g(x) = a + bx$ tale che:\
$$g(x) \\cdot (1 + x) \\equiv 1 \\pmod\{1 + x + 2x^2\}$$\
\
**Metodo: Algoritmo di Euclide Esteso**\
\
1. Dividiamo $(2x^2 + x + 1)$ per $(x + 1)$:\
   $$(2x^2 + x + 1) = (x + 1)(2x + 2) + 2$$\
\
2. Isoliamo il resto:\
   $$2 = (2x^2 + x + 1) - (x + 1)(2x + 2)$$\
\
3. Per ottenere 1 a sinistra, moltiplichiamo per l'inverso di 2 in $\\mathbb\{F\}_3$.\
   \
   In $\\mathbb\{F\}_3$: $2 \\cdot 2 = 4 \\equiv 1 \\pmod\{3\}$, quindi $2^\{-1\} = 2$.\
   \
   $$1 = 2(2x^2 + x + 1) - 2(x + 1)(2x + 2)$$\
\
4. Nel quoziente $\\mathbb\{F\}_3[x]/\\langle 2x^2 + x + 1 \\rangle$, il termine $2(2x^2 + x + 1) \\equiv 0$.\
   \
   Resta:\
   $$1 \\equiv -2(x + 1)(2x + 2) \\pmod\{2x^2 + x + 1\}$$\
\
5. In $\\mathbb\{F\}_3$: $-2 \\equiv 1 \\pmod\{3\}$, quindi:\
   $$1 \\equiv (x + 1)(2x + 2)$$\
\
**Verifica:** $(1 + x)(2 + 2x) = 2 + 2x + 2x + 2x^2 = 2x^2 + 4x + 2 \\equiv 2x^2 + x + 2$ in $\\mathbb\{F\}_3$.\
\
Poich\'e9 $2x^2 + x + 1 \\equiv 0$, abbiamo $2x^2 \\equiv -x - 1 \\equiv 2x + 2$.\
\
Sostituendo: $(2x + 2) + x + 2 = 3x + 4 \\equiv 0 + 1 = 1$ in $\\mathbb\{F\}_3$. \uc0\u10003 \
\
L'inverso di $(1 + x)$ \'e8 $\\mathbf\{2 + 2x\}$.\
\
---\
\
## Domanda 6\
\
**Sia $K := \\mathbb\{F\}_3[y]/\\langle 1 + y + 2y^2 \\rangle$. Quale dei seguenti elementi di $K$ \'e8 radice del polinomio $1 + x + 2x^2 \\in K[x]$?**\
\
**Opzioni:** $1 + y$, $1 + 2y$, $2 + y$, $2 + 2y$\
\
**Risposta corretta:** $1 + 2y$\
\
### Ragionamento\
\
**Step 1: Prima radice**\
\
Osserviamo che il polinomio $P(x) = 1 + x + 2x^2$ ha la stessa forma del polinomio che definisce il quoziente $K$.\
\
In $K$ vale: $1 + y + 2y^2 \\equiv 0$\
\
Quindi $x = y$ \'e8 una radice di $P(x)$ in $K$.\
\
**Step 2: Seconda radice (usando le formule di Vieta)**\
\
Per un polinomio $ax^2 + bx + c$, le radici $x_1, x_2$ soddisfano:\
- $x_1 + x_2 = -\\frac\{b\}\{a\}$\
- $x_1 \\cdot x_2 = \\frac\{c\}\{a\}$\
\
Per $P(x) = 2x^2 + x + 1$ (con $a = 2$, $b = 1$, $c = 1$):\
\
$$x_1 + x_2 = -\\frac\{1\}\{2\}$$\
\
In $\\mathbb\{F\}_3$: $2^\{-1\} = 2$ (poich\'e9 $2 \\cdot 2 = 4 \\equiv 1$), quindi:\
$$-\\frac\{1\}\{2\} = -1 \\cdot 2 = -2 \\equiv 1 \\pmod\{3\}$$\
\
Sapendo che $x_1 = y$:\
$$x_2 = 1 - y \\equiv 1 + 2y \\pmod\{3\}$$\
\
### Verifica\
\
**Verifica $x = y$:**\
$$P(y) = 1 + y + 2y^2 \\equiv 0 \\text\{ in \} K \\quad \\checkmark$$\
\
**Verifica $x = 1 + 2y$:**\
$$P(1 + 2y) = 1 + (1 + 2y) + 2(1 + 2y)^2$$\
\
Calcoliamo $(1 + 2y)^2$:\
$$(1 + 2y)^2 = 1 + 4y + 4y^2 \\equiv 1 + y + y^2 \\pmod\{3\}$$\
\
Quindi:\
$$P(1 + 2y) = 1 + 1 + 2y + 2(1 + y + y^2)$$\
$$= 2 + 2y + 2 + 2y + 2y^2$$\
$$= 4 + 4y + 2y^2$$\
$$\\equiv 1 + y + 2y^2 \\equiv 0 \\text\{ in \} K \\quad \\checkmark$$\
\
Entrambe le radici sono verificate. La risposta tra le opzioni \'e8 $\\mathbf\{1 + 2y\}$.\
\
---\
\
## Domanda 7\
\
**Siano $\\text\{Var\} = \\\{X, Y\\\}$ e $M = (S, R, V)$ il modello tale che $S = \\\{1, 2, 3\\\}$, $R = \\\{(1,1), (1,2), (2,2), (2,3), (3,2)\\\}$, $V(X) = \\\{1, 2\\\}$, $V(Y) = \\\{2, 3\\\}$. Dire qual \'e8 la formula $F$ tale che $M \\models_2 F$.**\
\
**Opzioni:** $\\Box(X \\lor Y) \\land \\neg X$, $\\Box X$, $\\Diamond \\neg Y$, $\\Box\\Diamond(X \\land Y)$\
\
**Risposta corretta:** $\\Box\\Diamond(X \\land Y)$\
\
### Ragionamento\
\
**Dati del modello:**\
- Stati: $S = \\\{1, 2, 3\\\}$\
- Relazione di accessibilit\'e0: $R = \\\{(1,1), (1,2), (2,2), (2,3), (3,2)\\\}$\
- $V(X) = \\\{1, 2\\\}$ \uc0\u8594  $X$ \'e8 vera negli stati 1 e 2\
- $V(Y) = \\\{2, 3\\\}$ \uc0\u8594  $Y$ \'e8 vera negli stati 2 e 3\
\
**Mondi accessibili da ciascuno stato:**\
- Da 1: $\\\{1, 2\\\}$\
- Da 2: $\\\{2, 3\\\}$\
- Da 3: $\\\{2\\\}$\
\
Verifichiamo ogni formula nel **mondo 2**:\
\
**1. $\\Box(X \\lor Y) \\land \\neg X$**\
\
- $\\neg X$ nel mondo 2: $X$ \'e8 vera in 2, quindi $\\neg X$ \'e8 **falsa**\
- La congiunzione \'e8 **falsa** \uc0\u10007 \
\
\
**2. $\\Box X$**\
\
"In tutti i mondi accessibili da 2, $X$ \'e8 vera"\
\
- Mondi accessibili da 2: $\\\{2, 3\\\}$\
- $X$ in 2: vera \uc0\u10003 \
- $X$ in 3: **falsa** (perch\'e9 $V(X) = \\\{1, 2\\\}$)\
\
$\\Box X$ \'e8 **falsa** \uc0\u10007 \
\
**3. $\\Diamond \\neg Y$**\
\
"Esiste almeno un mondo accessibile da 2 in cui $\\neg Y$ \'e8 vera"\
\
- Mondi accessibili da 2: $\\\{2, 3\\\}$\
- $\\neg Y$ in 2: $Y$ \'e8 vera \uc0\u8594  $\\neg Y$ \'e8 **falsa**\
- $\\neg Y$ in 3: $Y$ \'e8 vera \uc0\u8594  $\\neg Y$ \'e8 **falsa**\
\
Non esiste alcun mondo accessibile dove $\\neg Y$ \'e8 vera.\
\
$\\Diamond \\neg Y$ \'e8 **falsa** \uc0\u10007 \
\
\
**4. $\\Box\\Diamond(X \\land Y)$**\
\
"In tutti i mondi accessibili da 2, esiste almeno un mondo accessibile in cui $X \\land Y$ \'e8 vera"\
\
Mondi accessibili da 2: $\\\{2, 3\\\}$\
\
- **Dal mondo 2:** accessibili $\\\{2, 3\\\}$\
  - In 2: $X \\land Y = \\text\{vero\} \\land \\text\{vero\} = \\text\{vero\}$ \uc0\u10003 \
  - Quindi $\\Diamond(X \\land Y)$ \'e8 vera in 2 \uc0\u10003 \
\
- **Dal mondo 3:** accessibili $\\\{2\\\}$\
  - In 2: $X \\land Y = \\text\{vero\}$ \uc0\u10003 \
  - Quindi $\\Diamond(X \\land Y)$ \'e8 vera in 3 \uc0\u10003 \
\
Poich\'e9 $\\Diamond(X \\land Y)$ \'e8 vera in tutti i mondi accessibili da 2, abbiamo:\
\
$\\Box\\Diamond(X \\land Y)$ \'e8 **vera** \uc0\u10003 \
\
\
La risposta corretta \'e8 $\\mathbf\{\\Box\\Diamond(X \\land Y)\}$.\
\
}