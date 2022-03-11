# Šablona pro sh.gmh.wtf

Toto je šablona vytvořena výhradně pro projekt semináře z informatiky Oktávy a 4.A

## Základní barvy a jejich názvy
  - primary: #005a9c;
  - warning: #fcc100;
  - success: #72ea81;
  - dark: #343434;
  - light: #fafafe;
  - orange: #ff9800;
  - danger: #ca4343;


## Soubory

### header.html
Hlavička, kterou bude obsahovat každá stránka

### index.html
Ukázka použití šablony

### styles.css
Obsahuje veškeré stylování...
Je potřeba stáhnout, nahrát na server a linknout na ni pro fungování šablony

```html5
<link rel="stylesheet" href="./styles.css" />
```

## Použití

Šablona styluje mnoho věcí
- Tlačítka
- Inputy
- Text
- Oznámení
- Tabulky
- Galerie
- a další užitečné třídy
- Vše si můžete prohlídnout po stažení v index.html

### Tlačítka
- samotné tlačítko se nastyluje samo
- poté můžete použít třídy:
  - btn-primary, btn-warning, btn-orange, btn-danger, btn-dark, btn-light - pro změnu barevnosti
  - btn-sm, btn-lg, btn-wide - pro změnu velikosti

#### Příklad použití
```html
<button class="btn-warning btn-wide">
Tlačítko Primary
</button>

```

### Inputy
- Input se také nastyluje sám
- poté podobně jako u tlačítek existují třídy:
  - input-primary, input-warning, input-orange, input-danger, input-dark, input-light - pro změnu barevnosti

#### Příklad Použití 

```html
<input
  type="text"
  placeholder="Zadej Něco"
  class="input input-light"
/>
```

### Text
- Text je stylován automaticky takže se o něj vůbec nemusíte starat

### Oznámení
- 3 druhy: alert-success, alert-warning, alert-error

#### Příklad použití
```html
<div class="alert-success">
    <h3>Oznámení success</h3>
    <p>
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maiores
    exercitationem perspiciatis dolore tempora laboriosam iure qui nisi
    ullam dolorem architecto?
    </p>
</div>
```

### Tabulky
- Tabulky jsou též nastylované tak, že by měly fungovat samy

### Galerie
- Galerii vytvoříte přidáním třídy: gallery

#### Příklad Použití

```html
<div class="gallery">
    <a href="#"><img src="./ph.png" alt="Placeholder" /></a>
    <a href="#"><img src="./ph.png" alt="Placeholder" /></a>
    <a href="#"><img src="./ph.png" alt="Placeholder" /></a>
    <a href="#"><img src="./ph.png" alt="Placeholder" /></a>
    <a href="#"><img src="./ph.png" alt="Placeholder" /></a>
</div>
```

## Další užitečné třídy
### Padding 
velikosti jsou 1, 3, 5

 - px-1, px-3, px-5 - padding na X souřadnici
 - py-1, py-3, py-5 - padding na Y souřadnici
 - p-1, p-3, p-5    - padding všude
 - pt-1, pb-3, pl-5, pr-1 atd. - padding na vybraný směr

### margin 
Stejně jako u padding ale místo p je m

 - mx-1, mx-3, mx-5 - margin na X souřadnici
 - atd.

### Flex
 - justify-around, justify-between, justify-center - zarovná horizontálně
 - align-center, align-end - zarovná vertikálně
 - flex-wrap - umožní přejít na další řádek
 - flex-column - div bude vertikální

### Text 
 - tc-primary - barvy textu (warning, danger atd.)
 - text-center - vycentruje text
 
### Pozadí 
- bg-primary - změní barvu pozadí (warning, danger atd.)