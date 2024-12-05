# BSP_Master_SI

## Beskrivning
Hanterar manöver samt motionering av brandspjäll.

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| Enable | L | Aktiverar blocket. |
| Blocked | L | Blockerar blocket. |
| FireAlarm | L | Brandlarm. |
| ManeuverInput | L | Manöveringång vid normaldrift (ej larm). |
| RunningVent | L | Driftindikering från ventilation. |
| FireIndication | L | Brandindikering från spjäll/spjällgrupp. |
| NormalIndication | L | Normalindikering från spjäll/spjällgrupp. |
| ExerciseNow | L | Motionera spjäll nu. |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. BSP_GROUP_1) |
| User title | S | Namn på spjällgruppen, används till larm/eventloggning per automatik. (ex. ST11/21:1-5) |
| ExerciseWDay1 | X | Motionering veckodag [0=Av,1-7=Måndag-Söndag] |
| ExerciseWDay2 | X | Motionering veckodag [0=Av,1-7=Måndag-Söndag] |
| ExerciseWDay3 | X | Motionering veckodag [0=Av,1-7=Måndag-Söndag] |
| ExerciseDay | X | Dagar mellan motionering [0=Använd inställda dagar, 1-X=Använd inställda dagar] |
| ExerciseHour | X | Motioneringstimma [0-23] |
| DelayTime | I | Fördröjning innan motionering startar. |
| RunTime | I | Motioneringstid. |
| Exercise | L | 0=Ingen motionering, 1=Motionering. |
| ExerciseNormalOp | L | 0=Vent står stilla vid motionering, 1=Motionering vid normaldrift. |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| ManeuverFire | L | Utgång som drar vid larm. |
| ManeuverNormal | L | Utgång som drar vid normaldrift/släpper vid larm. |
| ExerciseActive | L | Motionering aktiv. |

## Namnstandard

SYSTEM_TYP

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| LB_1_BSP_GROUP_1 | Grupp 1 av brandspjäll till ventilation LB_1. |
