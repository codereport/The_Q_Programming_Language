## Q Built-in Functions

- [Link to Q for Mortals list](https://code.kx.com/q4m3/A_Built-in_Functions/)
- [Link to Q Reference Card list](https://code.kx.com/q/ref/)

|Keyword|Implementation|APL Equivalent|APL Name|
|:--:|:--:|:--:|:--:|
|`asc`|-|`⍵[⍋⍵]`|
|`avg`|`(sum x) % count x`|`+/÷⍴`|
|`avgs`|`(sums x) % 1 + til count x`|`{(+\⍵)÷⍳⍴⍵}`|
|`ceiling`|-|`⌈`|`ceiling`|
|`cut`|-|`{((⍳⍴⍵)∊⍺)⊂⍵}`|
|`deltas`|`(-) prior`|`{(⊃⍵),-2-/⍵}`|
|`desc`|-|`⍵[⍒⍵]`|
|`differ`|`(<>) prior`|`1,2≠/`|
|`each`|-|`¨`|`each`|
|`first`|`1 #`|`⊃`|`first`|
|`floor`|-|`⌊`|`floor`|
|`iasc`|-|`⍋`|`grade up`|
|`idesc`|-|`⍒`|`grade down`|
|`last`|`-1 #`|`¯1↑`|
|`max`|`(\|) over`|`⌈/`|
|`maxs`|`(\|) scan`|`⌈\`|
|`min`|`(&) over`|`⌊/`|
|`mins`|`(&) scan`|`⌊\`|
|`over`|-|`/`|`reduce`|
|`prd`|`(*) over`|`×/`|
|`prds`|`(*) scan`|`×\`|
|`raze`|-|`,`|`ravel`|
|`reverse`|-|`⌽`|`reverse`|
|`rotate`|`reverse (reverse y # x) , reverse y _ x`|`⌽`|`rotate`|
|`scan`|-|`\`|`scan`|
|`sum`|`(+) over`|`+/`|
|`sums`|`(+) scan`|`+\`|
|`where`|-|`⍸`|`where`|
