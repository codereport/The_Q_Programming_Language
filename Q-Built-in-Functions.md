## Q Built-in Functions

- [Link to Q for Mortals list](https://code.kx.com/q4m3/A_Built-in_Functions/)
- [Link to Q Reference Card list](https://code.kx.com/q/ref/)

|Keyword|Implementation|APL Equivalent|APL Name|
|:--:|:--:|:--:|:--:|
|`abs`|-|`\|`|`magnitude`|
|`all`|`0 < min`|`∧/`|
|`and`|`&`|`∧`|`and`|
|`any`|`0 < max`|`∨/`|
|`asc`|-|`⍵[⍋⍵]`|
|`avg`|`(sum x) % count x`|`+/÷⍴`|
|`avgs`|`(sums x) % 1 + til count x`|`{(+\⍵)÷⍳⍴⍵}`|
|`ceiling`|-|`⌈`|`ceiling`|
|`count`|-|`⍴`|`shape`|
|`cross`|`raze x,\:/:y`|`{,⍺∘.,⍵}`|
|`cut`|-|`{((⍳⍴⍵)∊⍺)⊂⍵}`|
|`deltas`|`(-) prior`|`{(⊃⍵),-2-/⍵}`|
|`desc`|-|`⍵[⍒⍵]`|
|`differ`|`(<>) prior`|`1,2≠/`|
|`each`|-|`¨`|`each`|
|`first`|`1 #`|`⊃`|`first`|
|`flip`|-|`⍉`|`transpose`|
|`floor`|-|`⌊`|`floor`|
|`iasc`|-|`⍋`|`grade up`|
|`idesc`|-|`⍒`|`grade down`|
|`in`|`any x =\:/: y`|`∊`|`membership`|
|`inter`|`x where x in y`|`∩`|`intersection`|
|`last`|`-1 #`|`¯1↑`|
|`ltrim`|`x where maxs " " <> x`|`{(∨\' '≠⍵)/⍵}`|
|`max`|`(\|) over`|`⌈/`|
|`maxs`|`(\|) scan`|`⌈\`|
|`min`|`(&) over`|`⌊/`|
|`mins`|`(&) scan`|`⌊\`|
|`or`|`\|`|`∨`|`or`|
|`over`|-|`/`|`reduce`|
|`prd`|`(*) over`|`×/`|
|`prds`|`(*) scan`|`×\`|
|`raze`|-|`,`|`ravel`|
|`reverse`|-|`⌽`|`reverse`|
|`rotate`|`reverse (reverse y # x) , reverse y _ x`|`⌽`|`rotate`|
|`rtrim`|`reverse ltrim reverse x`|`{(⌽∨\⌽' '≠⍵)/⍵}`|
|`scan`|-|`\`|`scan`|
|`sum`|`(+) over`|`+/`|
|`sums`|`(+) scan`|`+\`|
|`string`|-|`⍕`|`format`|
|`til`|-|`⍳`|`iota`|
|`trim`|`ltrim rtrim x`|`{⌽(∨\⌽' '≠⍵)/⍵} {(∨\' '≠⍵)/⍵}`|
|`union`|`x , y where not y in x`|`∪`|`union`|
|`where`|-|`⍸`|`where`|
