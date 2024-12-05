# BSP_STATUS_GROUP_SI

## Beskrivning
Hantering av indikering grupper av brandspjäll.

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| Status_X | L | Indikering av spjäll X. BSP_STATUS_GROUP kan finnas i olika mängder av X. |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| FireIndication | L | Utlöst läge till BSP_Master. |
| NormalIndication | L | Normalläge till BSP_Master. |

## Namnstandard

SYSTEM_TYP

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| LB_1_BSP_STATUS_GROUP_1 | Status grupp 1 av brandspjäll till grupp BSP_GROUP_1. |
