# Climatix IV Modbus

## Beskrivning

IV Climatix Aggregatet ska ställas till tilluftsreglering, inga tidkanaler på plats. Om från/rumsreglering sköt det i ducen och skicka in uträknat temperaturbörvärde till blocket

Tilluftsreglering: Ändra variabeln GT_TILL_1_BV_VS_Select = 0

Frånluft/Rumsreglering: Ändra variabeln GT_TILL_1_BV_VS_Select = 1

Sommar/Vinterväxling:  Låt GT_TILL_1_BV_VS_Select = SOMMARDRIFT_OOC_Output

Temperaturbörvärde: Börvärdet ställs in med temperaturbörvärde + kyldiff

Tryckreglering: Välj (0=Tryck) och knyt in önskat tryckbörvärde på till/frånluftstryck

Flödesreglering:  Välj (1=Flöde) och knyt in önskat flödesbörvärde på till/frånluftstryck

| Ingång | Signaltyp | Beskrivning|
| --- | --- | --- |
| Blocked | L | Blockerar blocket totalt. |
| BlockedAuto | L | Blockerar manöver i auto-läge |  
| StartStep1 | L | Start i Steg 1 |
| StartStep2 | L | Start i Steg 2 |
| StartStep3 | L | Start i Steg 3 |


| Inställningar | Signaltyp | Beskrivning |
| --- | --- | --- |
| Name | S | Namn på blocket (ex. CLIMATIX_IV) |
| User title | S | Används ej- namn hämtas från huvudblock (ex. LB_1, Sub system title "LA01") |
| TemperatureSetpoint | R | Börvärde tilluftstemperatur |
| SupplyPressureSetpointStep1 | R | Börvärde tilluftstryck Steg 1 |
| SupplyPressureSetpointStep2 | R | Börvärde tilluftstryck Steg 2 |
| SupplyPressureSetpointStep3 | R | Börvärde tilluftstryck Steg 3 |
| ExhaustPressureSetpointStep1 | R | Börvärde frånlufstryck Steg 1 |
| ExhaustPressureSetpointStep2 | R | Börvärde frånlufstryck Steg 2 |
| ExhaustPressureSetpointStep3 | R | Börvärde frånlufstryck Steg 3 |
| SupplyFlowSetpointStep1 | R | Börvärde tilluftsflöde Steg 1 |
| SupplyFlowSetpointStep2 | R | Börvärde tilluftsflöde Steg 2 |
| SupplyFlowSetpointStep3 | R | Börvärde tilluftsflöde Steg 3 |
| ExhaustFlowSetpointStep1 | R | Börvärde frånluftsflöde Steg 1 |
| ExhaustFlowSetpointStep2 | R | Börvärde frånluftsflöde Steg 2 |
| ExhaustFlowSetpointStep3 | R | Börvärde frånluftsflöde Steg 3 |
| Select | X | Handställning (0=Från, 1=Till, 2=Auto) |
| SelectStep | X | Handställning driftläge (0=Auto, 1=Från, 2=Steg 1, 3=Steg 2, 4=Steg 3) |
| TemperatureDiff | R | Dödzon mellan värme och kyldrift |
| FanMode | L | Reglertyp (0=Tryck, 1=Flöde) |
| SupplyPressureMin | R | Driftindikeringsgräns tilluftstryck |
| ExhaustPressureMin | R | Driftindikeringsgräns frånluftstryck |
| SupplyFlowMin | R | Driftindikeringsgräns tilluftsflöde |
| ExhaustFlowMin | R | Driftindikeringsgräns frånluftsflöde |


| Larm | Beskrivning |
| --- | --- | --- |
| ALARM_A1 | Summalarm A1 |
| ALARM_A2 | Summalarm A2 |
| ALARM_B | Summalarm B |
| ALARM_C | Summalarm C |
| ALARM_VVX_1 | VVX Summalarm |
| ALARM_TA1 | Summalarm tilluftsfläkt  |
| ALARM_FA1 | Summalarm frånluftsfläkt |
| LARM_VVX_1_VERKN | Låg Verkn.grad |
| ALARM_P1_LV | Summalarm CP1 Cirkulationspump Värme |
| ALARM_P2_LV | Summalarm CP2 Cirkulationspump Kyla |
| ALARM_FRYSV_1 | Frysvakt |
| ALARM_AVV_GT_TILL_1 | GT1 Avvikelse tilluft |
| ALARM_AVV_GT_FRAN_1 | GT2 Avvikelse frånluft |
| ALARM_AVV_GFP_TILL_1 | GP1 Hög Avvikelse |
| ALARM_AVV_GFP_FRAN_1 | GP2 Hög Avvikelse |
| ALARM_TF1_FILTERV1 | GP5 Filtervakt tilluft |
| ALARM_FF1_FILTERV1 | GP6 Filtervakt frånluft |
| ALARM_BRAND | Rök/Brandlarm |
| ManualAlarm | Handställningslarm |


| Utgångar | Signaltyp | Beskrivning |
| --- | --- | --- |
| GT_TILL_1_Output | R | Tilluftstemperatur |
| GT_FRAN_1_Output | R | Frånluftstemperatur |
| GT_UTELUFT_1_Output | R | Uteluftstemperatur |
| GT_FRYS_1_Output | R | Frysvakt |
| GT_RUM_1_Output | R | Rumstemperatur |
| GT_AVLUFT_1_Output | R | Avluftstemperatur |
| GT_VVXT_1_Output | R | Tilluftsgivare efter VVX |
| GP_TILL_1_Output | R | Tilluftstryck |
| GP_FRAN_1_Output | R | Frånluftstryck |
| GF_TILL_1_Output | R | Tilluftsflöde |
| GF_FRAN_1_Output | R | Frånluftsflöde |
| LV_SV_1_Output | R | Värmeventil |
| LK_SV_1_Output | R | Kylventil |
| VVX_1_Output | R | Utsignal återvinning |
| VVX_1_VERKN_Efficiency | R | Verkningsgrad återvinning |
| GT_TILL_1_SetPoint | R | Tilluftstemperatur börvärde |
| GT_TILL_1_SetPoint_Diff | R | Tilluftstemperatur Kyldiff |
| GT_TILL_1_SetPoint_Heat | R | Tilluftstemperatur Värmebörvärde |
| GT_TILL_1_SetPoint_Cool | R | Tilluftstemperatur Kylbörvärde |
| TF_1_SetPoint_Step_1 | R | Tilluftsfläkt börvärde Steg 1 |
| TF_1_SetPoint_Step_2 | R | Tilluftsfläkt börvärde Steg 2 |
| TF_1_SetPoint_Step_3 | R | Tilluftsfläkt börvärde Steg 3 |
| FF_1_SetPoint_Step_1 | R | Frånluftsfläkt börvärde Steg 1 |
| FF_1_SetPoint_Step_2 | R | Frånluftsfläkt börvärde Steg 2 |
| FF_1_SetPoint_Step_3 | R | Frånluftsfläkt börvärde Steg 3 |
| TF_1_Running | L | Drift tilluftsfläkt |
| FF_1_Running | L | Drift frånluftsfläkt |
| LV_P_1_Running | L | Drift Cirkulationspump värme |
| LK_P_1_Running | L | Drift Cirkulationspump kyla |
| StartOut | L | Utgång vid start av aggregat oberoende av steg  |
| RunMode | X | Driftläge (0=Off, 1=On/Comfort, 2=Economy, 3=-, 4=Osstp, 5=Nightcooling, 6=Unoccupied (Temp start), 7=Nightkick (Test temp), 8=Firedamper test, 9=Fire, 10=Stop, 11=Overrun, 12=Startup) |
| FanStep | X | Fläktsteg (0=Från, 1=Steg 1, 2=Steg 2, 3=Steg 3) |

## Namnstandard

SYSTEM_TYP

## TYP (exempel)

| Typ | Beskrivning |
| --- | --- |
| LB_1_CLIMATIX_IV | Climatixaggregat. |
