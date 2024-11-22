# LOG

## Beskrivning
Loggning av mätare/annan signal

![Alt text](img/MeterLogSI.PNG?raw=true "Bild")

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| Input | R | Ingång, från ex. VMM1_Energy |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. LOG_Energy) |
| Factor | R | Skalningsfaktor på loggsignalen |
| Reset | L | Nollställer loggning |

| Larm | Beskrivning |
| --- | --- |
| RefreshAlarm | Inga nya värden |
| DayHighAlarm | Hög dygnsförbrukning |
| MonthHighAlarm | Hög månadsförbrukning |

| Mätning/Loggning | Signaltyp | Beskrivning |
| --- | --- | --- |
| LastHour | R | Förbrukning föregående timme |
| LastDay | R | Förbrukning föregående dag|
| LastWeek | R | Förbrukning föregående vecka|
| LastMonth | R | Förbrukning föregående månad |
| LastYear | R | Förbrukning föregående år |
| LastMonday | R | Förbrukning föregående måndag |
| LastTuesday | R | Förbrukning föregående tisdag |
| LastWednesday | R | Förbrukning föregående onsdag |
| LastThursday | R | Förbrukning föregående torsdag |
| LastFriday | R | Förbrukning föregående fredag |
| LastSaturday | R | Förbrukning föregående lördag |
| LastSunday | R | Förbrukning föregående söndag |
| AccumHour | R | Förbrukning innevarande timme |
| AccumDay | R | Förbrukning innevarande dag|
| AccumWeek | R | Förbrukning innevarande vecka|
| AccumMonth | R | Förbrukning innevarande månad |
| AccumYear | R | Förbrukning innevarande år |

## Namnstandard

SYSTEM_TYP

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| LOG | Loggning mätare |


