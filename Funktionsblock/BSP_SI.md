# BSP_SI

## Beskrivning
Hantering av indikering och larm av brandspjäll. Skall kopplas vidare till BSP_Master (via BSP_STATUS_GROUP).

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| Enable | L | Aktiverar blocket. |
| Blocked | L | Blockerar blocket. |
| NORMAL | L | Normallägesindikering. Binds automatiskt till DI_%FullName% (t.ex DI_LB_1_BSP_1_NORMAL) |
| MOTION | L | Brandlägesindikering. Binds automatiskt till DI_%FullName% (t.ex DI_LB_1_BSP_1_MOTION) |
| Fire | L | Brandlarmsingång. Bör hämtas från BSP_Master. |
| Exercise | L | Motionering. Bör hämtas från BSP_Master. |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. BSP_1) |
| User title | S | Namn på brandspjäll (ex. ST10:1). Kommer användas i larm per automatik. |
| Reset | L | Reset av larm. |
| InverseIndications | L | Skiftar normal/brandindikeringar. |

| Larm | Beskrivning |
| --- | --- |
| WrongPosAlarm | Spjäll i fel läge. |
| ExerciseAlarm | Fel vid motionering av spjäll. |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Status | X | Status till gruppstatus. |

## Namnstandard

SYSTEM_TYP

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| LB_1_BSP_1 | Branspjäll i ventilation LB_1. |
