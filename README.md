# Uvod v programiranje v Python-u 
KŠOK - Uvod v programiranje v programskem jeziku Python. 

V naslednjih nekaj tednih bo potekalo 6 eno in pou urnih predavanj. Soočli se bomo z vsemi potrebnimi osnovami programiranja v Pythonu, pri zadnjem predavanju 
pa bomo probali to vse povezati in sprogramirati krajši programček. 

**Kontakt predavatelja ter Zoom:**  
- Liam Mislej  
  - liammislej@gmail.com  
  - zoom: coming soon  
V kolikor imate kakeršna koli vprašanja, rabite kakeršno koli pomoč pri programiranju izven ur predavanj mi lahko pišete na e-naslov in vam bom z veseljem pomagal.  

---

## Novice
Kakeršne koli novice bodo objavljene tukaj.

---

## Potek 

Posamezna predavanja ob prej določenih datumih/urah bodo potekala v dveh delih. V prvem delu bodo predavanja v drugem pa vaje, približno tako kot na faksu pri določenih predmetih.  
Pri predavanjih bom predaval snov(Powerpoint), povedal vse osnove ter se v določene stvari poglobil. Pri vajah bomo skupaj predavano uporabili v dejanskem programu, torej bomo pisali kodo, in probavali razne primere.

Približen potek posameznih predavanj je prikazan spodaj. Spotoma bom dodajal vse potrebne vire in osnutke. Nekatere stvari se bodo pojavle pred posameznimi predavanji nekatere pa kasneje. 

Na koncu bodo spodnji sklopi služili kot "plonk" listki, kjer bodo na kratko napisane in prikazane vse osnove s katerimi smo se soočli.

Tečaj bo sledil sklopom iz spodnjega vira, s tem, da bomo sklope bolj na podrobno predelali. 

[W3schools Python Tutorial](https://www.w3schools.com/python/default.asp)

Vsi uporabljeni oz. napisani programi se nahajajo v mapi Koda.

### Torek 4.5.2021 - Uvod v programiranje, osnovni pojmi, števila, nizi in ostale osnove

##### Python

Python je interpretni visokoravni večnamenski programski jezik. Interpretni(interpreted) pomeni, da se napisana koda izvaja postopoma brez potrebe po kompilaciji programa. Pomembno je vedeti, da se koda izvaja po vrsticah, prvo se izvede prva vrstica, nato druga, tretja, ... 



Nekateri programski jeziki uporabljajo razne znake(<code>{ }, ;, ...</code>) za ločevanje blokov kode, pri Pythonu to ni tako, uporablja se indentacijo(indente) za ločevanje blokov. Indent kot tak je le niz z, ponavadi 4-mi, presdledki. Krajše napišemo oz. natipkamo z tipko <code>Tab</code>, primer: 

Python  
```python
# To ni indentirano in vrne napako
if True:
print("Hello world")
```

```python
# To je pravilno indentirano
if True:
  print("Hello world")
```

Primer iste kode v programskem jeziku Java kjer se bloke deli z uporabo {, }:

```java
class HelloWorld {
    public static void main(String[] args) {
        if (True) {
            System.out.println("Hello, World!"); 
        }
    }
}
```

Vse to bo bolj razumljivo v prihodnosti(zankah, funkcijah, ...), ko bomo to potrebovali.

- Komentiranje (comments)  
- Spremenljivke (variables)
- Podatkovni tipi (data types)
- Print in Input
- Števila (numbers)
- Pretvorbe podatkovnih tipov (casting)
- Nizi (strings)
- Logične vrednosti (booleans)
- Operaterji (operators)

### Torek 11.5.2021 - Podatkovni tipi in zanke

- Seznami (lists/arrays)
- Tupli (tuples)
- Množice (sets)
- Slovarji (dictionaries)
- Uporabne integrirane metode in funkcije 
- While zanka (while loop)
- For zanka (for loop)

### Četrtek 13.5.2021 - Funkcije

- Funkcije (functions)
- Lambda funkcije (lambdas)


### Torek 18.5.2021 - Objektno programiranje 

- Razredi (classes)
- Dedovanje (inheritence)

### Četrtek 20.5.2021 - Uvod v knjižnice in njihovo uporabo

- Iteratorji (iterators)
- Obseg v pythonu, funkcije v funkcijah, globalne spremenljivke (scope)
- Moduli in uvažanje (modules and imports)
- PIP 
- Nekaj integriranih knjižnjic: Date, Math, JSON, OS
- Urejanje datotek (file handling)


### Torek 25.5.2021 - Uporaba zunanjih knjižnjic, prvi celotni program


