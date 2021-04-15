# Proměnné, datové typy, objekty
## Proměnné
- je označení pro identifikátor, který uchovává informaci při běhu programu
- proměnná může nabývat různých známých nebo neznámých informací, které se nazývají hodnota
- Jméno promněnné je obvyklá cesta k získání reference k uložené hodnotě v paměti počítače
- Separace jména a obsahu umožňuje použít jméno. které se používá nezávisle na přenesené informaci, kterou zastupuje
- Identifikátor ve zdrojovém kódu zastupuje nějakou hodnotu, která se za běhu může měnit
- Kompilátor musí nahradit symbolická jména proměnných za skutečné umíštění dat
### Práce s proměnnými
- V imperativních programovacích jazycích může být hodnota globálně adresována nebo změněna v jakémkoliv čase
- V čistě funkcionálních a logicky zaměřených jazycích jsou proměnné omezeny na jeden výraz a hodnoty si udržují po celou dobu svého životního cyklu kvůli požadavkům na referenční transparentnost
    - referenční transparentnost je vlastnost výrazů, kdy výraz lze vyhodnotit i bez ohledu na kontext
### Pointery, proměnné, reference
- pointer ukazuje na místo v paměti - vrací adresu
- promněnné vrací hodnotu z místa v paměti
- reference odkazuje na danné místo v paměti
### Typová kontrola
- Jsou buď:
    - Jazyky se statickou typovou kontrolou
        - Java, C++,...
        - Proměnná může nabývat hodnot pouze v nějakém rosahu
        - před proměnnou definujeme jakého datového typu promněná je
    - Jazyky s dynamickou typovou kontrolou
        - Python, javascript
        - hodnoty mají svůj datatyp nikoliv proměnné
### Alokace
- Identifikátor je přiřazen na adresu konkrétního bloku v paměti a operace této promněné manipulují pouze s tímto blokem paměti
## Datový typ
- definuje druh nebo význam hodnot, kterých smí nabývat proměnná nebo konstanta
- Datový typ je určen oborem hodnot a zároveň výpočetními operacemi, které lze s hodnotami tohoto typu provádět
### Jednoduché datové typy
- Elementární datové typy jsou většinou přímo zabudovány do jazyka, přičemž v běžně používaných jazycích nejsou parametrizovatelné
- Složitější typy pak mohou vznikat skládáním elementárních datových typů
### Typy
- Boolean
    - pravda a lež
    - pouze 1bit ale v paměti je to 1 bajt
- Byte/unsigned char
    - 8 bajtů
    - 0 - 255
- Integer/long int
    - 4 bajty
    - - 2 miliony až 2 miliony
- float
    - 4 bajty
    - desetina mista
## Objekty
- používá se o v OOP, což je programovací paradigma
- je to konkrétní datový objekt v paměti odvozený z nějakého vzoru - třídy
- Objekt představuje základní stevební prvek OOP
- jsou to jednotlivé prvky modelované reality
- jsou v programu jsou seskupeny do entit
- Objekty si pamatují svůj stav a navenek poskytují operace