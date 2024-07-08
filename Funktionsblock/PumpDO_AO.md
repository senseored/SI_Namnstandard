# Pump

## Beskrivning

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| StartIn | L | Startsignal |
| Input | R | Analog styrsignal |
| Blocked | L | Blockerar block |
| Running | L | Driftindikering |
| MotorProt | L | Ingång utlöst motorskydd |
| OutputManual | R | Analog styrsignal vid _Select = 1 |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. P_1) |
| User title | S | Namn på pump (ex. P01). Kommer användas i larm per automatik. |
| Select | Från/Manuell/Till/Auto |

| Larm | Beskrivning |
| --- | --- |
| ManualAlarm | Handställningslarm |
| SumAlarm | Summalarm |
| MProtAlarm | Motorskyddslarm |
| ExerciseAlarm | Motioneringslarm |
| BlockedAlarm | Block blockerat |
| BlockedAutoAlarm | Block blockerat i auto |
| ForcedONAlarm | Forcerat till |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| StartOut | L | Värde för länkning till andra block och/eller digital utgång. |
| Output | R | Styrsignal |
| Status | X | Status (0 = Av, 1 = Drift, 2 = Larm, 3 = Drift+Larm) |

## Namnstandard

SYSTEM_TYP

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| P_1 | Pump |

## Exempel på namn till en varmvattenkrets:

| Namn | Beskrivning |
| --- | --- |
| VV_1_P_1 | Cirkulationspump |



