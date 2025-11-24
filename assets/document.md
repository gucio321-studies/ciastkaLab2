# Powłoki elektronowe w atomie
W modelu Bohra (dobre przybliżenie) elektrony mogą poruszać się po orbitach stacjonarnych o stałej energii bez emisji promieniowania.
Elektrony mogą również przeskakiwać między tymi orbitami
- emitująć promieniowanie gdy przeskok z wyższej na niższą
- absorbując promieniowanie gdy przeskok z niższej na wyższą.

Częstotliwość emitowanego/absorbowanego promieniowania jest związana z różnicą energii między tymi poziomami energetycznymi w nastęþujący sposób:

$$
h \nu = E_i - E_j
$$

gdzie:
- $h$ to stała Plancka,
- $\nu$ to częstotliwość promieniowania,
- $E_i$ i $E_j$ to energie odpowiednich poziomów energetycznych.

Sam zaś elektron może mieć energię skwantowaną określoną wzorem:

$$
E_n = - \frac{m k^2 e^4}{2 \hbar^2 n^2}
$$

```{admonition} główna liczba kwantowa
w powyższym wzorze $n$ nazywane jest główną liczbą kwantową. może przyjmować wartości $n \in \mathbb{N}$
```

## Nazewnictwo powłok
Powłoki elektronowe nazywamy według nastęþująćego schematu: $nl$, gdzie:
- n - główna liczba kwantowa
- l - litera na podstawie orbitalnej liczby kwantowej $l$ wg następującej tabeli:

| l | 0 | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|---|
| litera | s | p | d | f | g | h | i |

## Notacja Siegbaha
Notacja używana w spektroskopii rentgenowskiej do opisu przejść.
Przejścia opisujemy według schematu: $X_{y}$, gdzie:
- $X$ - powłoka docelowa (na którą przechodzi elektron) oznaczona literą
- $y$ - różnica głównych liczb kwantowych między powłoką początkową a docelową (litera grecka).

| N | litera | $\Delta n$ | litera grecka |
|---|---|---|---|
| 1 | K | 1 | $\alpha$ |
| 2 | L | 2 | $\beta$ |
| 3 | M | 3 | $\gamma$ |


# Prawo Moseley'a
Opisuje zależność liczby atomowej $Z$ a częstotliwością promieniowania fluorescencyjnego emitowanego przez atom.
DLa danego przejścia (np. $K_\alpha$) częstotliwość ta wynosi:

$$
\sqrt{\nu} = k (Z - \sigma)
$$

gdzie:
- $k$ - stała zależna od przejścia
- $\sigma$ - stała ekranowania

# Działąnie spektrometru XRF

```{figure} spektrometr.png
:scale: 50%
:align: center

Schemat działąnia spektrometru
```

## Lampa rentgenowska
To urządzenie emitujące elektrony przyspieszane napięciem $U_x$ które uderzają w anodę wybijając z niej kwanty promieniowania rentgenowskiego.

## Detektor półprzewodnikowy
1. Detektor półprzewodnikowy (np. krzemowy) działa na zasadzie generacji par elektron-dziura pod wpływem padającego promieniowania rentgenowskiego.
2. Złącze P-N jest spolaryzowane w kierunku zaporowym, co powoduje natychmiastowe przyciągnięcie powstałych nośników ładunków do elektrod.
3. Powstaje impuls prądu, którego parametry odpowiadają energii padającego fotonu.
