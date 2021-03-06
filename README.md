# Jakobsonizátor

- case syncretisms according to Roman Jakobson's theory
- this script takes input data (langugage grammar) and generates html output (page cointaining colorful tables)

usage: `./cases.py < stsl.txt > stslo.html`

you can preview output here: https://is.muni.cz/auth/www/393725/stslo.html

Input file format:
- comments are lines starting with `-`
- write cases in format `case<tab>singular<tab>dual<tab>plural`
- cases are N, G, D, A, V, L, I
- V is optional
- everything else will be simply printed out
- string `[edit]` will be deleted


example of input file (it is copy&paste from wikipedia)
```
Nouns[edit]

o-stems[edit]
Masculine gender ("town")
-	Singular	Dual	Plural
N	grad-ъ	grad-a	grad-i
G	grad-a	grad-u	grad-ъ
D	grad-u	grad-oma	grad-omъ
A	grad-ъ	grad-a	grad-y
V	grad-e	grad-a	grad-i
L	grad-ě	grad-u	grad-ěxъ
I	grad-omь	grad-oma	grad-y

Neuter gender ("wine")
-	Singular	Dual	Plural
N	vin-o	vin-ě	vin-a
G	vin-a	vin-u	vin-ъ
D	vin-u	vin-oma	vin-omъ
A	vin-o	vin-ě	vin-a
V	vin-o	vin-ě	vin-a
L	vin-ě	vin-u	vin-ěxъ
I	vin-omь	vin-oma	vin-y
```
