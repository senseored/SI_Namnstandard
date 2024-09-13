# MEDEL

## Beskrivning
Medeluträkning utetemperatur (annan signal vid behov)

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| Input | R | Signal för medeluträkning |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. GT_TILL_1) |
| User title | S | Namn på givare (ex. GT11). Kommer användas i larm per automatik. |
| INST_TimeConstant | R | Inställbar tid för medeluträkning |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| DAY_MovingAverage | R | Medelvärde dygn |
| INST_MovingAverage | R | Medelvärde inställbar tid |

## Namnstandard

SYSTEM_TYP_NAMN

