# PID/Regulator

## Beskrivning

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| Input | R | Värde som skall regleras |
| Setpoint | R | Börvärde som värde skall regleras till |
| Blocked | L | Blockerar PID |
| Enable | L | Stopp/Start PID |
| Reset | L | Nollställer PID |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. VV_1_GT_TILL_1_PID) |
| User title | S | Används ej |
| MinOutput | R | Min utsignal |
| MaxOutput | R | Max utsignal |
| OutputManual | R | Manuell utsignal |
| Select | X | 0%/Manuell/Auto |
| PGain | R | P-förstärkning |
| ITime | R | I-tid |
| DTime | R | D-tid |
| MaxDGain | R | Max D-förstärkning |
| BlockedOutput | R | Utsignal i blockerat läge |

| Larm | Beskrivning |
| --- | --- |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Output | R | Utsignal |

## Namnstandard

SYSTEM_TYP_PID

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |

## Exempel på namn till en varmvattenkrets:

| Namn | Beskrivning |
| --- | --- |
VV_1_GT_TILL_1_PID

