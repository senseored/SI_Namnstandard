# Larm

## Namnstandard

SYSTEM_TYP_NAMN_LARMSUFFIX

Alla larmsuffix skall sluta med "Alarm", för att föeenkla larmhantering i bilder/skript.

## Givare/Mätvärden
| Namn | Beskrivning |
| --- | --- |
| _SensorAlarm | Givarfel |
| _HighAlarm | Höglarm |
| _LowAlarm | Låglarm |
| _DiffAlarm | Avvikelselarm |
| _HighAAlarm | Höglarm A-larm |
| _LowAAlarm | Låglarm A-larm |
| _DiffAAlarm | Avvikelselarm A-larm|

## Utgångar/Styrsignaler/Ingångar
| Namn | Beskrivning |
| --- | --- |
| _ManualAlarm | Handläge |
| _NotRunAlarm | Driftfelslarm |
| _MotorProtAlarm | Utlöst motorskydd |
| _SumAlarm | Summalarm |
| _MaintAlarm | Lång drifttid |
| _BlockedAlarm | Funktion blockerad |

## Exempel på larm

| Namn | Beskrivning |
| --- | --- |
| VV_1_GT_TILL_1_HighAlarm | Tappvarmvatten höglarm |
| VV_1_GT_TILL_1_LowAlarm | Tappvarmvatten låglarm |
| VV_1_P1_SumAlarm | VVC-pump summalarm |
| VV_1_SV_1_ManualAlarm | Varmvattenventil handläge |
