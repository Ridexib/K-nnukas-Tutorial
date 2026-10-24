# Kuidas oma ala kaitsta

`/claim` kaitseb sinu ehitist ja asju teiste mängijate eest.

## 1. Vali ala kaks nurka

Mine oma tulevase ala ühte nurka ja kirjuta:

```text
/claim setpos
```

Mine diagonaalis vastasnurka ning kirjuta sama käsk uuesti. Ala võib olla kõige rohkem **350 × 350 plokki**. Vali mõlemad nurgad viie minuti jooksul.

> **Pildi koht 1:** ekraanipilt mängust, kus on näha kavandatava ala kaks vastasnurka. Lisa pildile selged märgid „1. nurk” ja „2. nurk” ning näita vestluses `/claim setpos` kinnitust.

## 2. Loo ala

Anna alale nimi, näiteks:

```text
/claim create kodu
```

Nimes ei tohi olla tühikuid. Kui valitud ala kattub kellegi teise kaitstud alaga, vali uued nurgad.

Mängijal saab olla kuni **5 ala maailma kohta**. Esimene ala maksab **3 000 €** ja iga järgmine on 1,5 korda kallim, kui eelmised alad on alles:

| Ala | Hind |
| --- | ---: |
| 1. | 3 000 € |
| 2. | 4 500 € |
| 3. | 6 750 € |
| 4. | 10 125 € |
| 5. | 15 187,50 € |


## 3. Vaata ja halda oma ala

| Soov | Käsk |
| --- | --- |
| Vaata ala asukohta | `/claim show minu_kodu` |
| Teleporteeru alale | `/claim tp minu_kodu` |
| Kutsu sõber alale | `/claim friend invite minu_kodu MängijaNimi` |
| Eemalda sõber alalt | `/claim friend uninvite minu_kodu MängijaNimi` |
| Eemalda ala | `/claim remove minu_kodu` |

`/claim show` näitab ala koordinaate ja pakub klikitavat teleportimist. Teleportimine maksab **100 €**. Kui alale pole eraldi teleportimiskohta määratud, võib see viia ka maa alla.

> **Pildi koht 2:** ekraanipilt pärast käsku `/claim show minu_kodu`. Näita vestluses ala koordinaate ja klikitavat teleportimisvõimalust ning võimalusel kaitstud ala piire mängumaailmas.

Kui käsk ununeb, kirjuta `/claim`.
