# Grafika1 Ukol1 
**deadline! 4.cviko!!**
 [Zadání](https://github.com/Maruch-MrSky/Grafika1-Ukol1?tab=readme-ov-file#zad%C3%A1n%C3%AD-z-olivy)
 [Plán](https://github.com/Maruch-MrSky/Grafika1-Ukol1?tab=readme-ov-file#pl%C3%A1n)
 [Progress](https://github.com/Maruch-MrSky/Grafika1-Ukol1?tab=readme-ov-file#progress-viktoooor)
 [Poznámky a postřehy](https://github.com/Maruch-MrSky/Grafika1-Ukol1?tab=readme-ov-file#pozn%C3%A1mky-a-post%C5%99ehy)

## Zadání z olivy 
1. **Rasterizace úsečky, čáry s barevným přrechodem a n-úhelníku**
 - Vytvořte program pro kreslení úsečky zadané dvěma libovolnými koncovými body [x1,y1] a [x2,y2].
 - Koncové body zadávejte interaktivně pomocí tzv. pružné čáry. Stisknutím tlačítka myši zadáte první vrchol, při tažení myší se bude vykreslovat aktuální úsečka společně s již vykreslenou scénou a při uvolnění tlačítka se potvrdí koncový vrchol.
 - K implementaci použijte rozhraní a třídy definované na cvičeních. Třídy případně upravte nebo doplňte o potřebné metody. *Návrhy třídy Point, Line a LineRasterizer naleznete v modulu task1 (viz Oliva-obsah-ukázky a návody)*.
 - Vytvořte třídu *FilledLineRasterizer* dědící z abstraktní třídy *LineRasterizer* a správně implementující libovolný algoritmus pro rasterizaci úsečky. Do komentáře zapište, o jaký algoritmus se jedná, jeho výhody a nevýhody, případně jiná jeho specifika. 
 - Prozkoumejte třídy *Canvas, CanvasKey, CanvasPaint, …, CanvasRasterBufferedImage* (v Olivě ukázky a návody), řešící hlavní aplikační třídu a UI. Soustřeďte se na interface *Raster* a třídu *RasterBufferedImage* a použijte ji pro vaše řešení.
 - Třídy zakomponujte do aplikace, která bude interaktivně zadávat body tvořící vrcholy n-úhelníku. Využijte ukázku *CanvasRasterBufferedImage*.
 - Zkušenější studenti mohou použít aplikační logiku z modulu *task2*, primárně určeného pro druhou úlohu. Tyto ukázky aplikačního řešení nejsou dogma, můžete je modifikovat nebo navrhnout vlastní. Snažte se o rozdělení aplikace na smysluplné třídy a zachovejte koncept rozhraní a tříd *Raster, Point, Line a LineRasterizer*.
 - Vytvořte si vhodnou třídu *Polygon* pro ukládání vrcholů. *Je vhodnější ukládat vrcholy ne hrany z důvodu zajištění uzavřenosti útvaru, viz druhá úloha*.
 - Vrcholy zadávejte interaktivně: stisknutím tlačítka myši vytvořte nový bod spojený s dvěma již vytvořenými vrcholy, např. s prvním a posledním. Tažením kreslete pružnou čáru k oběma vrcholům a uvolněním tlačítka přidejte bod do seznamu vrcholů n-úhelníku.
 - Přidejte řežim (po stisku klávesy Shift) pro kreslení vodorovných, svislých a úhlopříčných úseček. První bod je zadán stiskem, druhý určen na základě polohy při tažení myši, tak aby se vybral nejbližší koncový bod z možné vodorovné, svislé nebo úhlopříčné úsečky.
 - Implementujte algoritmus vykreslující úsečku s barevným přechodem mezi dvěma koncovými barevnými odstíny. 
 - Implementujte funkci na klávesu C pro mazání plátna a všech datových struktur.
 - **Bonus**: Upravte program tak, aby bylo možné souřadnice jednotlivých vrcholů editovat myší. Například při stisku pravého tlačítka myši naleznete nejbližší vrchol a tažením mu nastavíte novou souřadnici. Podobně i přidávání nových vrcholů bude nový vrchol umístěn do nejbližší hrany.
Při hodnocení je kladen důraz na funkčnost programu pro libovolně zadané koncové body, na přesnost vykreslení a na kvalitu návrhu a čitelnost kódu. Kód vhodně rozdělte do rozhraní a tříd. 
Kód očistěte od ladicích či pokusných nefunkčních částí.
Odevzdávejte prostřednictvím Olivy, před odevzdáním si znovu přečtěte pravidla odevzdávání semestrálních projektů a průběžných úloh.

## Plán
 - plocha pro vykreslování (Canvas - JPanel a JFrame)
 - matika vykreslování přímky
 - třída Polygon pro ukládání vrcholů
 - M1 - vyhreslování čáry *(hold-drag-release)*
 - Shift + M1 - vodorovné čáry 
 - usečka dvou barev
 - C - maže Canvas *(hehe přebarvit cely canvas na černo/bílo místo čištění hehe)*

## Progress (VIKTOOOOR!!)

## Poznámky a postřehy
 - zatím nic :c
