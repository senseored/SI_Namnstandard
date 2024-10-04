# AI/Analog Ingång

## Beskrivning

(img/Analog Input SI.png)

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| Input | R | Ingång, binds till AI_-ingång. |
| SetPoint | R | Börvärde, binds till aktuellt börvärde. Används för presentation av aktuellt börvärde i display, bild, loggning och uträkning av larm. |
| BlockLow | L | Blockering av låglarm. |
| BlockHigh | L | Blockering av höglarm. |
| BlockDiff | L | Blockering av differenslarm. |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. GT_TILL_1) |
| User title | S | Namn på givare (ex. GT11). Kommer användas i larm per automatik. |
| LowAlarmLimit | R | Låglarmsgräns. |
| HighAlarmLimit | R | Höglarmsgräns. |
| DiffAlarmLimit | R | Avvikelselarmgräns. |
| LowAAlarmLimit | R | Låglarmsgräns A-larm. |
| HighAAlarmLimit | R | Höglarmsgräns A-larm. |
| DiffAAlarmLimit | R | Avvikelselarmgräns A-larm. |
| AlarmHysteresis | R | Larmhysteres. |
| EnableHLDiff | L | Hög/låglarm som avvikelse mot börvärde. |
| AllowNaN | L | Tillåt !NaN. |
| Offset | R | Kalibrering. |
| MinOutput | R | Min utsignal. |
| MaxOutput | R | Max utsignal. |
| LowSensorLimit | R | Låggräns givarfel. |
| HighSensorLimit | R | Höggräns givarfel. |
| SensorCnt | I | Inställbar tid för oförändrat värde, -1 = inaktiverat. |

| Larm | Beskrivning |
| --- | --- |
| SensorAlarm | Givarfel |
| HighAlarm | Höglarm. Beroende på EnableHLDiff används absolut larmgräns eller relativ mot börvärde. |
| LowAlarm | Låglarm. Beroende på EnableHLDiff används absolut larmgräns eller relativ mot börvärde. |
| DiffAlarm | Avvikelselarm |
| HighAAlarm | Höglarm A-larm. Beroende på EnableHLDiff används absolut larmgräns eller relativ mot börvärde. |
| LowAAlarm | Låglarm A-larm. Beroende på EnableHLDiff används absolut larmgräns eller relativ mot börvärde. |
| DiffAAlarm | Avvikelselarm A-larm |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Output | R | Skalat värde för visning och länkning till andra block. |
| OP | L | Summalarmsutgång (för färgändring givarsymbol, användning i Webport och liknande. |

## Namnstandard

SYSTEM_TYP_NAMN

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| GT | Temperatur |
| GP | Tryck |
| GM | Fukt |
| GX | CO/CO2 |
| GF | Flöde |

## NAMN (exempel)

| Namn | Beskrivning |
| --- | --- |
| TILL | Tillopp/Tilluft |
| RETUR | Retur |
| EXP | Expansion |

## Exempel på namn till en varmvattenkrets:

| Namn | Beskrivning |
| --- | --- |
| VV_1_GT_TILL_1 | Tappvarmvatten |
| VV_1_GT_RETUR_1 | VVC-temperatur |

