## Algoritmus
Je posloupnost instrukcí pro řešení problému (definic existuje mnoho; tahle definice není definice, ale jen intuitivní představa; algoritmus MUSÍ SKONČIT, jinak není algoritmus!)
- **Problém** - *vstup, který má jeden výstup* (množina vstupů, pro každý vstup je jeden výstup; může se také chápat jako přiřazení, které každému vstupu přiřazuje odpovídající výstup)
- **Instrukce** - *jednoznačný a srozumitelný pokyn* (aby mu počítač rozuměl a uměl ho zpracovat)
- **Řešení problému algoritmem** - Algoritmus řeší problém, pokud pro každý vstup I (kterému odpovídá výstup O), platí:\
Vykonávání instrukcí podle algoritmu se vstupem I se po konečném počtu kroků zastaví a na výstupu je O.

- *Fakta o algoritmech a problémech*
  - Existují i problémy, které nelze řešit algoritmem
  - Některé problémy jsou lehčí než jiné. Zabývá se tím teorie vyčíslitelnosti. *??? slide 18 ???*
  - Má smysl dělit problémy podle obtížnosti a algoritmicky řešitelných problémů na rychle řešitelné a ty, pro které není rychlý algoritmus znám.
  - Jeden algoritmus může být lepší/efektivnější než druhý, zabývá se tím teorie složitosti a je to prakticky velmi důležité.

- **Jak popsat algoritmus**
  - **Přirozeným jazykem**\
    *plus* - snadno srozumitelné\
    *minus* - může být nejednoznačné a zdlouhavé
  - **Programovacím jazykem**\
    *plus* - jednoznačné\
    *plus* - vytvořit program je pak lehké, protože ho stačí jen přepsat; rozumí tomu programátoři\
    *minus* - obsahuje i zbytečné (nepodstatné) detaily
  - **Pseudokódem** (neobsahuje tolik podrobností jako programovací jazyk)\
    *plus* - snadno pochopitelný i pro lidi, kteří nemají zkušenosti s programováním\
    *plus* - srozumitelný a úsporný popis algoritmů\
    *plus* - umožňuje snadný přepis do programovacích jazyků\
    *minus* - ten přepis pro implementaci do programovacího jazyka
  - Další: (např. vývojové diagramy)

- **Správnost algoritmu**\
Pro každý algoritmus musíme ověřit zdali je správný (algoritmus pro každý možný vstup skončí po určitém počtu kroků se správným výstupem).\
Abychom dokázali, že algoritmus není správný, musíme najít důkaz (příklad vstupu, který dostane špatný výstup nebo algoritmus neskončí vůbec).
- **Složitost algoritmu**\
Dává informaci, jak je algoritmus kvalitní a můžeme ho porovnávat s jinými algoritmy
  - *Časová složitost* - rychlost vykonávání algoritmu nehledě na hardware (počet kroků)\
  vyjadřuje závislost trvání výpočtu algoritmu na velikosti vstupních dat (pro každý vstup může být jiná doba výpočtu)\
  je to tedy funkce (zobrazení), která přiřadí velikosti vstupních dat trvání výpočtu (číslo)\
  funkce T: N -> N, n (velikost vstupu) -> T(n) (trvání výpočtu, to počítáme v instrukcích, které algoritmus musí pro daný vstup vykonat; v nejhorším případě/v průměrném případě)
  - *Paměťová složitost* - kolik paměti bude potřebovat
- **Optimalita algoritmu**\
Můžeme dokázat, že existuje (nebo neexistuje) efektivnější/lepší algoritmus pro řešení daného problému.
