# Variabel.rwlv
SI_CB\Views\SubView\Variabel.rwlv

## Beskrivning
Vy för lista för upp till 10 st värden.
Värden skapas genom %SubView_Controller%%SubView_Object%%SubView_Setting#X% där X är 4 för första visning, 9 för andra, 14 för tredje, 19 för fjärde etc.

## Variabler

## Setting
[#1,#2,#3,#4,#5]

### Förklaringar
1: Beskrivning av värdet (t.ex. "Börvärde:")
2: Enhet (t.ex kPa), eller kommaseparerad lista om listvisning (t.ex. "Nej [0],Ja [1]")
3: Antal decimaler som visas i nummervisning (t.ex. "2" för 0.00)
4: Variabel som ska visas (enligt beskrivning)
5: 0 = Ej ändringsbar siffra
    1 = Ändringsbar siffra
    2 = Ej ändringsbar lista
    3 = Ändringsbar lista
