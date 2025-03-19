# Larmlista.rwlv
SI_CB\Views\SubView\Larmlista.rwlv

## Beskrivning

![Alt text](img/AnalogInput_Larm.PNG?raw=true "Bild")

Visar upp till 9st larm med larmgränser (typ Variabel.rwlv, fast larm istället).

## Variabler

## Setting
[#1;#2;#3;#4;#5]

### Förklaringar
1: Beskrivning av larmet (t.ex. "GT11 Gräns höglarm B-larm:")

2: Larmgräns/variabel (t.ex. LB1_GT_TILL_1_LowAlarmLimit)

3: Enhet (t.ex kPa)

4: Antal decimaler som visas i nummervisning (t.ex. "2" för 0.00)

5: Larmvariabel (t.ex LB1_GT_TILL_1_LowAlarm)


## SubView
| Namn | Beskrivning | Exempel |
| --- | --- | --- |
| Title | Namn på vy | Larmgränser |
| File | Filnamn | AnalogInput_Larm.rwlv |
| Controller | Duc | %Controller%. |
| Object | Givare | %VS1%_GT_TILL_1 |
