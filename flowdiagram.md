```mermaid
graph TD;
Config-->airports;
airports-->Addnew;
Addnew-->ICAO;
ICAO-->Lookup;
Lookup-->GroundHandlingCost-->Fuel;
GroundHandlingCost-->ExcelcolumnaJ;
Fuel-->DelaAalaN;
```
