# Markdown in Visual Studio Code 
## Datei zum verlinken
Markdown ist eine vereinfachte Auszeichnungssprache, die von John Gruber und Aaron Swartz entworfen und im Dezember 2004 mit Version 1.0.1 spezifiziert wurde. Ein Ziel von Markdown ist eine leicht lesbare Ausgangsform bereits vor der Konvertierung. Als Auszeichnungselemente wurden daher vor allem Auszeichnungsarten verwendet, die in Plain text und E-Mails üblich sind. Auch andere Auszeichnungssprachen mit ähnlichen Zielen zur Lesbarkeit – wie reStructuredText oder Textile – hatten Einfluss auf die Syntax. Der MIME-Type lautet text/markdown.

## Mathematische Formeln
Mathematische Formeln werden in Markdown in $$ eingefasst
### Beispiele
1. $ a^2 + b^2 + c^2 $
---
2. $ \sqrt{2x+5} $
---
3. $\frac{3x+5-7}{2x-1}$
---
4. $\int_0^2{\pi}$
---
5. $\lim\limits_{n\rightarrow \infty}{a_n}$
---
6. $\sum $

## Darstellen von Code
Code wird in Markdown in vier Backticks eingefasst
###Beispiele
#### Java
````Java
for(int i=0; i<=10; i++){
    System.out.println("Hallo Welt"+i)
}
````
#### Python
```` Python
for i in range(1,6):
    x = ((n-1)*x+a/(x**(n-1)))/n
    print ('   ',i,'    ',x)
````
## Einfache Formatierung
Dieses Wort ist **fett** und dieses Wort ist _kursiv_!
>**Notiz:** Hier ist eine Notiz
---
[X] Dies ist eine Chekbox
### Tabellen
| Name | Nachname | Noch zu Zahlen | Grund|
|:-  |:-: | :-:|-:|
| Jakob | Waldnam | 5000 Geld | Weil er mir den Wald nahm|
| Sebastian | Fresse | 2000 Geld | Weil er nie leise ist|
| Mitchi | Lidl | 7000 Geld | Weil ich keine Schokolade von ihm bekomme|
---
### Listen
1. punkt 1
2. Punkt 2
    - Unterpunkt 2.1
    - Unterpunkt 2.2
- Punkt 3
### Links
 [GÜÜÜÜGÖÖÖÖÖL](https://www.google.de/)
 [Kein Virus](./Test.md)
