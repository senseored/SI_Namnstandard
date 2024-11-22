# DO/Digital Output

## Beskrivning

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| StartIn | L | Ingång, från ex. PID_VV1_GT_TILL_1_Output |
| Blocked | L | Blockerad utgång, vid 1 forcera till 0. |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. BEL_1) |
| User title | S | Namn på ställdon/utsignal (ex. Ytterbelysning). Kommer användas i larm per automatik. |
| Select | X | Från/Till/Auto |
| Invert | L | Inverterar _Command |

| Larm | Beskrivning |
| --- | --- |
| ManualAlarm | Handställningslarm |
| BlockedAlarm | Blockering aktiv |
| SumAlarm | Summalarm (något av de andra larmen) |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| StartOut | L | Värde för länkning till andra block och/eller analog utgång. |
| DisplayOut | L | Skalat värde för visning och loggning. |
| OP | L | Summalarmsutgång (för färgändring symbol, användning i Webport och liknande. |

## Namnstandard

SYSTEM_TYP

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| BEL | Belysning |

## Exempel på namn till en varmvattenkrets:

| Namn | Beskrivning |
| --- | --- |

