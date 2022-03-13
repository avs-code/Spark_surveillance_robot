```mermaid
graph TD;
Config-->airports;
airports-->Addnew;
Addnew-->ICAO;
ICAO-->Lookup;
Lookup-->GroundHandlingCost;
GroundHandlingCost-->ExcelcolumnaJ;
Fuel-->De la A a la N;
```
