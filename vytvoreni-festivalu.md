# Vytvoření festivalu
1. V hlavní nabídce vyberte Nová stránka a volbu Festival
2. Zadejte:
   1. Kód festivalu, kód bude vidět v URL stránky a v aplikace kod.wannado.eu _{{ book.code }}_ 
   2. Název _{{ book.title }}_
   3. Popis _{{ book.description }}_

3. Klikněte na tlačítko Další krok
4. Můžete odebírat a přidávat libovolné komponenty (následující je pouze příklad). [Nápovědu k editoru obsahu](/editor-obsahu.md)
   1. Vyberte komponentu typu festival_baseInfo a vyplňte:
      1. festival_baseInfo_title - název festivalu, např. PRAHA
      2. festival_baseInfo_date - datum konání festivalu
      3. festival_baseInfo_textPart - krátký úvodní text o festivalu
      4. Klikněte na Vytvořit a vytvořte tyto komponenty
         1.festival_textCommon
         2. festival_navigation x3
     5. Vyberte komponent festival_textCommon a upravte atribut festival_textCommon_text
     6. Jděte zpět do komponenty festival_baseInfo
     7. Vyberte komponentu Button a atribut button_link_external vyplňte odkazem na registrační formulář
     8. Tři komponenty festival_navigation upravte takto:
        1. První:
           1. festival_navigation_text = Sporty a kluby
           2. festival_navigation_scrollTo = sportyKluby 
        2. Druhá:
            1. festival_navigation_text = Program
            2. festival_navigation_scrollTo = program
        3. Třetí:
            1. festival_navigation_text = Navigovat
            2. festival_navigation_scrollTo = navigovat
   2. Jděte zpět do kořenové komponenty   
   3. Vyberte komponentu festival_sportClubs
      1. festival_sportClubs_link vyplňte odkazem na registrační formulář
   4. Jděte zpět do kořenové komponenty   
   5. Vyberte komponentu program
      1. Vyberte přílohu pro map_program, což je detailní program festivalu
   6. Jděte zpět do kořenové komponenty   
   7. Vyberte komponentu map
      1. Vyplňte map_address adresou, kde se bude konat festival. Adresa musí být dohledatelná na google maps.
      2. Vyberte přílohu pro map_detailLink, což je detailní mapa festivalu
   8. Nastavení aplikace naleznete [zde](/nastaveni-aplikace.md)
5. Klikněte na tlačítko Publikovat
6. Zkontrolujte si publikaci tlačítkem Přejít na Stránku
   
         
         
TIP: Můžete se podívat, jak jsou nastaveny jiné festivaly.       
