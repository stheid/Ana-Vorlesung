    ,.                    ,.   ,.         .                         
   / |   ,-. ,-.          `|  /   ,-. ,-. |  ,-. ,-. . . ,-. ,-.    
  /~~|-. | | ,-|    ===    | /    | | |   |  |-' `-. | | | | | |    
,'   `-' ' ' `-^           `'     `-' '   `' `-' `-' `-^ ' ' `-|    
                                                              ,|    
                                                              `'

Das Skriptum wird mit XeLaTeX compiliert und benötigt gnuplot

Das Projekt ist immer in Arbeit, wenn das Skriptum also mal nur
ein paar Zeilen lang ist, einfach in 'ner Stunde noch mal schaun.

Das fertig übersetzte Skript gibt es hier:
https://www.dropbox.com/s/d6b8on7f8gh91aw/Ana%20Skriptum.pdf


 Bugs bitte mit folgendem Muster an bugfixes@ccjordan.de
″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″″
┌──────────────────────────────────────────────────────────────┐
│ Betreff: Vorlesung »Nummer«                                  │
│  -  -  -  -  -  -  -  -  -                                   │
│ Inhalt:                                                      │
│ »Kapitelnummer«.»Unterkapitelnummer«                         │
│                                                              │
│ »Unterüberschrift«.Zeile»Nummer«(in dieser Unterüberschrift) │
│ (Seite »Nummer«)                                             │
│                                                              │
│ »alt« : »neu«                                                │
└──────────────────────────────────────────────────────────────┘

×× Bsp:
┌──────────────────────────────────────────────────────────────┐
│ Betreff: Vorlesung 09	                                       │
│  -  -  -  -  -  -  -                                         │
│ 4.27                                                         │
│                                                              │
│ Beweis#1.Zeile3 (Seite 42)                                   │
│                                                              │
│ b+...b_n : b_0+...+b_n                                       │
└──────────────────────────────────────────────────────────────┘


um das Dokument zu bauen:

 * man benötigt gnuplot

 $ xelatex --shell-escape main.tex
