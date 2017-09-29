# Nastavení aplikace

## Vytvoření festivalu

Pro nastavování aplikace je potřeba mít vytvořený [festival](/vytvoreni-festivalu.md "Přejít na vytvoření festivalu").

## Soutěž

Pro soutěž je zvláštní struktura, její nastavení naleznete [zde](/vytvoreni-souteze-na-festivalu.md)

## Sporty

Pro sporty je zvláštní struktura, sporty [přidané k festivalu](/pridani-sportu.md) budou vidět v aplikaci.

## Detailní mapa a program

1. V hlavní nabídce v sekci Editace vyberte Festival Informace a váš festival
2. Vyberte komponentu typu map
   1. Upravte atribut map\_detailLink na detailní mapu 
3. Vyberte komponentu typu program
   1. Upravte atribut program\_detail na detailní program
4. Klikněte na Publikovat

## Mapa, bonusy/slevy, pravidla v aplikaci

1. V hlavní nabídce v sekci Editace vyberte Festival Informace a váš festival
2. Vyberte/Vytvořte komponentu typu festivalApp
3. Vyberte vytvořenou komponentu
   1. Vyplňte atribut emptyPageFestival\_map\_image obrázkem s mapou festivalu
   2. Vyplňte atribut emptyPageFestival\_pravidla odkazem na pravidla pro soutěž
4. Vytvořte komponentu typu emptyPageFestival\_sleva
   1. Pro obrázkovou verzi slevy vyplňte:
      1. emptyPageFestival_slevaimage odkazem na obrázek se slevou_
      2. emptyPageFestival\_sleva\_buttonText značkou slevy, např. Bambule
   2. Pro textovou verzi slevy vyplňte:
      1. emptyPageFestival\_sleva\_text1 např. Nakupuj se slevou 500 Kč na www.protrenink.cz sportovní oblečení značky Under Armour.
      2. emptyPageFestival\_sleva\_text2 např. Sleva platí od 9.9.2017 – 23.9.2017 pro nákupy nad 1 000 Kč. Na využití slevy nevzniká právní nárok.
      3. emptyPageFestival\_sleva\_important např. Slevový kód: 12345SPORTACEK
      4. emptyPageFestival\_sleva\_buttonText značkou slevy např. 500 Kč na Under Armour
5. Klikněte na Publikovat



