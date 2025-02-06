# SubView

## Beskrivning
Vyn för knappar/visning av värden etc.

## Variabler

Det finns 9 st knappar/vyer att utnyttja (SubView1-SubView9). I tabellen nedan beskrivs de som SubViewX istället för 1, 2, 3... etc.

| Namn | Beskrivning | Exempel |
| --- | --- | --- |
| ControllerSelected | Följer med från gamla standarden. Kan användas i vyer som %ControllerSelected% | %Controller% |
| System | Följer med från gamla standarden. Kan användas i vyer som %System% | VS_1 |
| SubViewX_Enable | Kan sättas i "No [0]" för att dölja knapp. | No [0], Yes [1] |
| SubViewX_Title | Titel på knappen/vyn. | Börvärden, Larm |
| SubViewX_File | Fil som visas vid tryck på knappen. | Variabel.rwlv, Kurva.rwav |
| SubViewX_Controller | Används i vyer som %SubView_Controller%. Om alla variabler ligger i samma duc kan detta användas. Om inte, går den att lämnas tom. | %Controller%. |
| SubViewX_Object | Används i vyer som %SubView_Object%. Se vyers beskrivning för förklaring. | VS_1_GT_TILL_1 |
| SubViewX_Setting | Används i vyer som %SubView_Setting%. Är ofta uppdelad i en array, t.ex [A;B;C] - där SubView_Setting#1=A, SubView_Setting#2=B etc. | kWh, [kWh;1;min] |
| Window title | Fönstertitel | %VS1_NAMN% Tillopp |
