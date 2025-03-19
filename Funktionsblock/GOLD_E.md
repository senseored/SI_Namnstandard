# GOLD_E

## Beskrivning
GOLD E/F+. Aggregatet skall ställas in på konstant tilluftsreglering, inga tidkanaler på plats. Om från/rumsreglering sköt det i ducen och skicka in uträknat temperaturbörvärde till blocket.

| Ingång | Signaltyp | Beskrivning |
| --- | --- | --- |
| Blocked | L | Blockerar blocket totalt. |
| BlockedAuto | L | Blockerar manöver i auto-läge. |
| StartHalf | L | Start i halvfart. |
| StartFull | L | Start i helfart. |

| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. GOLD_E) |
| User title | S | Används ej - namn hämtas från huvudblock (ex. LB_1, user title LA01) | 
| Goldnamn | S | Namn på aggregatet i project builder (ex. LB_GOLD_E_LB1). PLA/ELA hämtas automatiskt  och skriv/läsvärden kommer fungera. |
| TemperatureSetpoint | R | Börvärde tilluftstemperatur. |
| SupplyPressureHalfSetpoint | R | Börvärde tilluftstryck halvfart. |
| SupplyPressureFullSetpoint | R | Börvärde tilluftstryck helfart. |
| ExhaustPressureHalfSetpoint | R | Börvärde frånluftstryck halvfart. |
| ExhaustPressureFullSetpoint | R | Börvärde frånluftstryck helfart. |
| SupplyFlowHalfSetpoint | R | Börvärde tilluftsflöde halvfart. |
| SupplyFlowFullSetpoint | R | Börvärde tilluftsflöde helfart. |
| ExhaustFlowHalfSetpoint | R | Börvärde frånluftsflöde halvfart. |
| ExhaustFlowFullSetpoint | R | Börvärde frånluftsflöde helfart. |
| Stoptype | X | Stopptyp (0 = Totalstopp, 1 = Normalstopp, 2 = Utökat normalstopp, 3 = Auto) |
| OutputStatus | X | Status av aggregat. Auto[0],Stopp[1],Halvfart[2],Helfart[3],Stopp med automatik[4],Stopp utan nattkyla[5] |
| SupplyPressureMin | R | Driftindikeringsgräns tilluftstryck. |
| ExhaustPressureMin | R | Driftindikeringsgräns frånluftstryck. |
| SupplyFlowMin | R | Driftindikeringsgräns tilluftsflöde. |
| ExhaustFlowMin | R | Driftindikeringsgräns frånluftsflöde. |
| Select | X | Handställning (0=Från, 1=Halvfart, 2=Helfart, 3=Auto) |

| Larm | Beskrivning |
| --- | --- |
| A_LARM | Summalarm A |
| B_LARM | Summalarm B |
| BRAND_LARM | Brandlarm |
| EXT_LARM | Externt larm |
| VARMEBATT_LARM | Värme summalarm |
| KYLBATT_LARM | Kyla summalarm |
| GIVARFEL_LARM | Givarfel larm |
| GT_TF_LARM | Temperatur hög avvikelse |
| AVV_GPF_LARM | GP/GF Avvikelselarm |
| VVX_1_LARM | VVX Summalarm |
| FILTERV_1_LARM | Filtervakt summalarm |
| SERVICE_LARM | Servicelarm |
| TF_1_LARM | Tilluftsfläkt larm |
| FF_1_LARM | Frånluftsfläkt larm |
| ELB_1_LARM | Elbatteri överhettning |
| START_LOG | Startlogg |
| TF_1_LOG | Tilluftsfläktlogg |
| FF_1_LOG | Frånluftsfläktlogg |
| TF_1_RT_MaintAlarm | Servicelarm tilluft |
| FF_1_RT_MaintAlarm | Servicelarm frånluft |
| ManualAlarm | Handställningslarm |

| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| GT_TILL_1_Output | R | Tilluftstemperatur |
| GT_FRAN_1_Output | R | Frånluftstemperatur |
| GT_RUM_1_Output | R | Rumstemperatur |
| GP_TILL_1_Output | R | Tilluftstryck |
| GP_FRAN_1_Output | R | Frånluftstryck |
| GF_TILL_1_Output | R | Tilluftsflöde |
| GF_FRAN_1_Output | R | Frånluftsflöde |
| LV_SV_1_Output | R | Utsignal värme |
| LK_SV_1_Output | R | Utsignal kyla |
| VVX_1_Output | R | Utsignal återvinning |
| VVX_1_VERKN_Efficiency | R | Verkningsgrad återvinning |
| TF_1_Running | L | Drift tilluftsfläkt |
| FF_1_Running | L | Drift frånluftsfläkt |
| StartOut | L | Utgång vid start av aggregat (hel eller halvfart) |

## Namnstandard

SYSTEM_TYP

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| LB_1_GOLD_E | Goldaggregat. |
