# AI/Analog Ingång

## Beskrivning

| Ingång | Beskrivning |
| --- | --- |
| Input | Ingång, binds till AI_-ingång. |
| SetPoint | Börvärde, binds till aktuellt börvärde. Används för presentation av aktuellt börvärde i display, bild, loggning och uträkning av larm. |
| BlockLow | Blockering av låglarm. |
| BlockHigh | Blockering av höglarm. |
| BlockDiff | Blockering av differenslarm. |

| Inställningar | Beskrivning |
| --- | --- |
| Name | Namn på blocket (ex. GT_TILL_1) |
| User title | Namn på givare (ex. GT11). Kommer användas i larm per automatik. |
| LowAlarmLimit | Låglarmsgräns. |
| HighAlarmLimit | Höglarmsgräns. |
| DiffAlarmLimit | Avvikelselarmgräns. |
| LowAAlarmLimit | Låglarmsgräns A-larm. |
| HighAAlarmLimit | Höglarmsgräns A-larm. |
| DiffAAlarmLimit | Avvikelselarmgräns A-larm. |
| AlarmHysteresis | Larmhysteres. |
| EnableHLDiff | Hög/låglarm som avvikelse mot börvärde. |
| AllowNaN | Tillåt !NaN. |
| Offset | Kalibrering. |
| MinOutput | Min utsignal. |
| MaxOutput | Max utsignal. |
| LowSensorLimit | Låggräns givarfel. |
| HighSensorLimit | Höggräns givarfel. |
| SensorCnt | Inställbar tid för oförändrat värde, -1 = inaktiverat. |

| Larm | Beskrivning |
| --- | --- |
| SensorAlarm | Givarfel |
| HighAlarm | Höglarm. Beroende på EnableHLDiff används absolut larmgräns eller relativ mot börvärde. |
| LowAlarm | Låglarm. Beroende på EnableHLDiff används absolut larmgräns eller relativ mot börvärde. |
| DiffAlarm | Avvikelselarm |
| HighAAlarm | Höglarm A-larm. Beroende på EnableHLDiff används absolut larmgräns eller relativ mot börvärde. |
| LowAAlarm | Låglarm A-larm. Beroende på EnableHLDiff används absolut larmgräns eller relativ mot börvärde. |
| DiffAAlarm | Avvikelselarm A-larm |

| Utgångar | Beskrivning |
| --- | --- |
| Output | Skalat värde för visning och länkning till andra block. |
| OP | Summalarmsutgång (för färgändring givarsymbol, användning i Webport och liknande. |

## Namnstandard

SYSTEM_TYP_NAMN

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| GT | Temperatur |
| GP | Tryck |
| SV | Ventil |
| P | Pump |
| GM | Fukt |
| GX | CO/CO2 |
| GF | Flöde |
| TF | Tilluftsfläkt |
| FF | Frånluftsfläkt |
| CF | Cirkulationsfläkt |

## NAMN (exempel)

| Namn | Beskrivning |
| --- | --- |
| TILL | Tillopp/Tilluft |
| RETUR | Retur |
| EXP | Expansion |

## Exempel på namn till en varmvattenkrets:

| Namn | Beskrivning |
| --- | --- |
| VV1_GT_TILL_1 | Tappvarmvatten |
| VV1_GT_RETUR_1 | VVC-temperatur |

