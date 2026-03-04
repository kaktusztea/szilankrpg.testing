## Távolsági harcrendszer - példák

CÉ: lövész képességei, fegyver "célzási képessége". Előre kiszámolt.

alapelv: a távolsággal és a célpont jellegének változásával exponenciálisan nehezedik a találat.
Ezért egy szorzás művelet van a VÉ meghatározásában, amiben 2 változó vesz részt.

### Szorzó fogalma
a célpont jellegét határozzuk meg vele. Ezek összege adja a "Szorzó" értékét. Hányszor kapod meg a távolságarányos büntit (táv/Osztó).
- \+ méret
- \+ mozgás
- \+ láthatóság

### Osztó fogalma
az adott fegyvert mennyire sújtja a távolság növekedése
- 1: kő
- 2: dobótőr
- 3: íj
- 4: nyílpuska


### VÉ képlet

```
VÉ = Szorzó  x  (Távolság / Osztó)
```


```
 Szorzó: KM számolja

 Távolság/Osztó: JK számolja

 VÉ: KM számolja
```


---
### Példák

#### 1.
Dobótőr/kő dobása 15 méterre (álló sörösdoboz)

Cellaszám = 8  (15 / 2)
Szorzó = 3+5 = 8
VÉ = 64

---
#### 2.

Kard dobása 15 méterre egy álló sörösdobozra

Cellaszám = 15 / 1 = 15
- Táv: 15 m
- Osztó: 1  (hajításra nem alkalmas)

Szorzó: 3x (álló) + 5x (doboz "alma" méretű) = 8x

VÉ = 8 x 15 = 120


---
#### 3.
Álló cél (ember) 15m dobótőrrel
Cellaszám = 15 / 2 = 8
Szorzó: 3x
VÉ = 8 x 3 = 24

---
#### 3.
Menekülő lovas 30 méterre íjásszal (ló is jó).

Cellaszám = 30 / 3 = 10
Szorzó = 8 (gyors, egyenletes) - 2 (lovas) = 6
VÉ = 6 x 10 = 60

Ugyanez cikázva (15-2):
VÉ = 13 x 10 = 130
