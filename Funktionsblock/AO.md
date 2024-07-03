# AO/AAM/Analog Output

## Beskrivning

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| Input | R | Ingång, från ex. PID_VV1_GT_TILL_1_Output |
| Blocked | L | Blockerad utgång, vid 1 forcera till 0. |
| OutputManual | R | Manuell utsignal |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. SV_1) |
| User title | S | Namn på ställdon/utsignal (ex. SV11). Kommer användas i larm per automatik. |
| Select | X | Från/Manuell/Auto |
| Invert | L | Inverterar _Output mot _Input, men låter _DisplayOutput = _Input. |

| Larm | Beskrivning |
| --- | --- |
| ManualAlarm | Handställningslarm |
| BlockedAlarm | Blockering aktiv |
| SumAlarm | Summalarm (något av de andra larmen) |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Output | R | Värde för länkning till andra block och/eller analog utgång. |
| DisplayOutput | R | Skalat värde för visning och loggning. |
| OP | L | Summalarmsutgång (för färgändring symbol, användning i Webport och liknande. |

## Namnstandard

SYSTEM_TYP

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| SV | Ventil |
| FO | Styrsignal frekvensomformare |
| TF | Tilluftsfläkt |
| FF | Frånluftsfläkt |
| CF | Cirkulationsfläkt |

## Exempel på namn till en varmvattenkrets:

| Namn | Beskrivning |
| --- | --- |
| VV1_SV_1 | Varmvattenventil |

