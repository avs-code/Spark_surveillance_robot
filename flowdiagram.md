```mermaid
graph TD;
Config-->airports;
airports-->Addnew;
Addnew-->ICAO;
ICAO-->Lookup;
Lookup-->Ground_Handling_Cost-->Fuel;
Ground_Handling_Cost-->Excel_columna_J;
Fuel-->De_la_L_a_la_N;
```
