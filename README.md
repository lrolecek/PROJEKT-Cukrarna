# Cukrárna

- [Cíl úkolu](#Cíl-úkolu)
- [Grafické zadání](#Grafické-zadání)
- [Obsah v HTML](#Obsah-v-HTML)

Než začneš s projektem cokoliv dělat, přečti si prosím celý tento text až do konce.

Za úkol máš nakódovat design podle grafického návrhu. Jedná se o úvodní stránku webu fiktivní cukrárny. Na výsledný vzhled projektu se podívej na obrázku *ukazka-vysledku.jpg*.

![Ukázka výsledku](ukazka-vysledku.jpg)


## Cíl úkolu

Cílem projektu je procvičit si použití různých technik:
- **Flexbox**
  - tento úkol je plný flexboxů
  - pomocí flexboxu udělej horní proužek s logem a menu
  - všechny sekce, kde je obrázek a vedle něj text, udělej také flexboxem. Textovou polovinu a obrázek můžeš pomocí flexboxu navzájem k sobě vertikálně vycentrovat.
  - nabídka dortíků je také flexbox, ale to už ti asi bylo jasné dávno
  - na horní banner s cupcaky flexbox nepotřebuješ - to je jenom sekce s obrázkem na pozadí, kde obsah má velký pravý padding (nebo margin)
- **Margin a padding**
  - v tomto úkolu nepotřebuješ žádné pozicování - vše vyřešíš jen pomocí flexboxu a marginu a paddingu
  - nezapomeň, že například nadpisy a odstavce mají ve výchozím stylu prohlížeče nastavený margin nahoru a dolů. Někdy je potřeba jeden z těchto marginů vynulovat (např. nad nadpisem), aby se ti nesčítal s paddingem prvku, ve kterém nadpis leží, a nad nadpisem tak nebyla větší mezera než chceš.
  - pamatuj na základní poučku:
    - chci-li obsah prvku odsadit od jeho okraje, použiji padding
    - chci-li odsunout dva prvky od sebe navzájem, použiji margin


## Grafické zadání

Všechny potřebné rozměry, použitá písma, barvy, apod. najdeš na obrázku *zadani-ukolu.png*. Spoustu z těchto informací máš připravenou také v komentáři v souboru *style.css*.

![zadání úkolu](zadani-ukolu.png)


## Obsah v HTML

- v HTML najdeš pouze obsahové elementy (nadpisy, odstavce, obrázky)
- sama si do HTML musíš dopsat další strukturu, která je nutná, abys mohla HTML nastylovat podle grafického zadání
- musíš vymyslet, do jakých prvků obsah zabalíš a jaké třídy jim přidáš
- nezapomeň si připojit správná písma z Google Fonts
