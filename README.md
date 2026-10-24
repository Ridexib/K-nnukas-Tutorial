# Kuidas oma ala kaitsta

`/claim` kaitseb sinu ehitist ja asju teiste mängijate eest.

## 1. Vali ala kaks nurka

Mine oma tulevase ala ühte nurka ja kirjuta:

```text
/claim setpos
```

Mine diagonaalis vastasnurka ning kirjuta sama käsk uuesti. Ala võib olla kõige rohkem **350 × 350 plokki**. Vali mõlemad nurgad viie minuti jooksul.

<img width="1731" height="909" alt="image" src="https://github.com/user-attachments/assets/efd69da1-8c93-49ca-887f-3c2fda53f055" />


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
| Vaata ala asukohta | `/claim show kodu` |
| Teleporteeru alale | `/claim tp kodu` |
| Kutsu sõber alale | `/claim friend invite kodu MängijaNimi` |
| Eemalda sõber alalt | `/claim friend uninvite kodu MängijaNimi` |
| Eemalda ala | `/claim remove kodu` |

`/claim show` näitab ala koordinaate ja pakub klikitavat teleportimist. Teleportimine maksab **100 €**. Kui alale pole eraldi teleportimiskohta määratud, võib see viia ka maa alla.

<img width="1308" height="81" alt="image" src="https://github.com/user-attachments/assets/774b8d8b-cde2-4f47-8a55-757c82ea021e" />

Kui käsk ununeb, kirjuta `/claim`.
