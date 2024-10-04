# Pump

## Beskrivning

![Alt text](img/PumpAnalogSI.PNG?raw=true "Bild")

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

| Drifttidsmätning | Signaltyp | Beskrivning |
| --- | --- | --- |
| TotalHours | Counter | Total drifttid (timmar/del) |
| TotalMinutes | Counter | Total drifttid (minuter/del) |
| MaintenanceHours | Counter | Tid sedan service (timmar/del) |
| MaintenaneMinutes | Counter | Tid sedan service (minuter/del) |
| ThisDayHours | Counter | Drifttid idag (timmar/del) |
| ThisDayMinutes | Counter | Drifttid idag (minuter/del) |
| PrevDayHours | Counter | Drifttid igår (timmar/del) |
| PrevDayMinutes | Counter | Drifttid igår (minuter/del) |
| TwoDaysAgoHours | Counter | Drifttid förrgår (timmar/del) |
| TwoDaysAgoMinutes | Counter | Drifttid förrgår (minuter/del) |
| ThisWeekHours | Counter | Drifttid innevarande vecka (timmar/del) |
| ThisWeekMinutes | Counter | Drifttid innevarande vecka (minuter/del) |
| PrevWeekHours | Counter | Drifttid föregående vecka (timmar/del) |
| PrevWeekMinutes | Counter | Drifttid föregående vecka (minuter/del) |
| ThisMonthHours | Counter | Drifttid innevarande månad (timmar/del) |
| ThisMonthMinutes | Counter | Drifttid innevarande månad (minuter/del) |
| PrevMonthHours | Counter | Drifttid föregående månad (timmar/del) |
| PrevMonthMinutes | Counter | Drifttid föregående månad (minuter/del) |
| ThisYearHours | Counter | Drifttid innevarande år (timmar/del) |
| ThisYearMinutes | Counter | Drifttid innevarande år (minuter/del) |
| PrevYearHours | Counter | Drifttid föregående år (timmar/del) |
| PrevYearMinutes | Counter | Drifttid föregående år (minuter/del) |
| TotalStarts | Counter | Starter totalt |
| ThisDayStarts | Counter | Starter idag |
| PrevDayStarts | Counter | Starter igår |
| TwoDaysAgoStarts | Counter | Starter förrgår |
| ThisWeekStarts | Counter | Starter innevarande vecka |
| PrevWeekStarts | Counter | Starter föregående vecka |
| ThisMonthStarts | Counter | Starter innevarande månad |
| PrevWeekStarts | Counter | Starter föregående månad |
| ThisYearStarts | Counter | Starter innevarande år |
| PrevYearStarts | Counter | Starter föregående år |

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



