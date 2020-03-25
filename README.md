# Kata19: Szólánc

### Írj egy programot, ami megoldja a szólánc rejtvényeket.

Létezik egy rejtvény, amelynél az a kihívás, hogy olyan szóláncokat hozz létre, amely egy bizonyos szóval kezdődik és egy megadott szóval ér véget.
A szólánc összes elemének létező szavakból kell állnia és minden szónak csak egyetlen egy betűvel szabad különböznie az előzőtől.

Például a "cat" szótol a "dog" szóig a következő lánccal:
>  1. cat
>  2. cot
>  3. cog
>  4. dog
  
A lényege ennek a katának, hogy írj egy olyan programot, ami a kezdő és befejező szó megadása után szóláncot hoz létre köztük szótár segítéségevel.

Plusz programozási mókaként írasd ki a legrövidebb szóláncot, ami megoldja a rejtvényt.

### Példák:

##### Például a _"lead"_ szót _"gold"_-ba négy lépés alatt lehet leírni:
>  1. _lead_
>  2. load
>  3. goad
>  4. _gold_
  
##### Vagy a _"ruby" "code"_-ba írásához hat lépés szükséges:
>  1. _ruby_ 
>  2. rubs 
>  3. robs 
>  4. rods 
>  5. rode 
>  6. _code_

----

Mihelyst működik a kód, próbáld meg lemérni az időt. Az említett példákhoz kevesebb mint egy másodopercre van szükség?
A lefutáshoz szükséges idő egyenlő mindkét irányba, előre fele és hátrafele is? (Tehát a "lead"-"gold" szólánc ugyanannyi idő mint a "gold"-"lead"?)
