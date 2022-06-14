# **Lattergas (N2O) på grisestalden**

### **Beregning:**

**Beregning af lattergas på stald** 

$$N_2O_{stald} = (N_{gris} + N_{strøelse}) \cdot Tab_{N2OStald} \cdot VM_{stald} $$

Hvor: 

 * Tab<sub>N2OStald</sub>: Direkte N2O tab i stalden, % af N ab dyr, ses i tabellen nederst
 * VM<sub>stald</sub>: Effekten af evt. valgte virkemidler på stalden

**Beregning af kg N ab gris, N<sub>gris</sub>, afhænger af dyretypen:** 

*Slagtegris + FRATS + smågris (konv. + øko)* 

$$N_{gris} = \frac{\frac{T \cdot Fe \cdot R}{P}-T \cdot N}{1000} $$

*Årssøer, konv + øko* 

$$N_{gris} = \frac{\frac{SF \cdot f_{so} \cdot R}{1000}}{P} - k_{so} \cdot f_{so} - \frac{V_{ind} \cdot V_{salg} \cdot N}{1000} \cdot f_{so}$$

$$---$$

Hvor: 

Tilvæksten, T, beregnes:
$$ T = (V_{slagt}  \cdot \Delta_d) - V_{ind} $$

og
 * Fe: Fesv pr kg tilvækst = input fra landmanden el standard (se SAFK-24)
 * R: Råprotein g pr foderenhed = se KLI-282
 * P: Protein til N = 6,25
 * N: N pr kg tilvækst = SKAL INDGÅ I TABEL
 * SF (sofoder pr årsso) = Input fra foderberegning el. standard fra tabel
 * f<sub>so</sub>: so-faktor, konv. = 0,7, øko = 0,5
 * k<sub>so</sub>: Korrektionsfaktor for soen = 1,98
 * V<sub>salg</sub>: vægt ved salg/afvænning
 * V<sub>slagt</sub>: Slagtevægt = input fra landmanden el standard (se SAFK-24)
 * Δ<sub>d</sub> = 1,31
 * V<sub>ind</sub>: Indsættelsesvægt = input fra landmanden el standard (se SAFK-24)

**Beregning af kg N fra strøelse**
$$ N_{strøelse} = Halm \cdot Z $$

 * Halm, kg halm per dyr, ses i tabellen nederst
 * Z: kg N pr. kg strøelse = 0,00425

 
|Dyretype C_2004|Kode dyretype C_2029|Staldtype C2005|Kode staldsystem C_2030|Tab<sub>N2OStald</sub>|Halm|
|---|---|---|---|---|---|
|1 producerede slagtesvin,| | | | | |
| |1512|delvis spaltegulv med 50-75 % fast gulv|7|0,2%|3|
| |1512|delvis spaltegulv med 25-49 % fast gulv |8|0,2%|3 |
| |1512|drænet gulv + spalter (33/67)|3|0,2%|0 |
| |1512|fast gulv |4|0,2%|13 |
| |1512|Dybstrøelse, opdelt lejeareal |5|0,37%|35 |
| |1512|Dybstrøelse|6|1%|70 |
|1 produceret FRATS, kon.| | | | | |
| |1520|Delvis spaltegulv med 50-75% fast gulv|2|0,2%|4|
| |1520|Delvis spaltegulv med 25-49% fast gulv|3|0,2%|4 |
| |1520|Drænet gulv + spalter (33/67)|4|0,2%|0 |
| |1520|Fast gulv|5|0,2%|15,5 |
| |1520|Dybstrøelse, opdelt lejeareal|6|0,37%|37,5 |
| |1520|Dybstrøelse|7|1%|83 |
|1 producerede slagtesvin, økologiske| | | | | |
| |1516|Udendørs|1|0,4% |30|
| |1516|Delvis spaltegulv inde. Løbegård (50/50) ude|2|0,2%|10 |
| |1516|Dybstrøelse hele arealet inde. Løbegård med fast/drænet gulv + spaltegulv (50%/50%)|3|0,56%|30 |
| 1 årsso m. 32,2 grise til 6,7 kg, 70% andel fra løbe- og drægtighedsstald |      |                                           |   |       |
|                                                                           | 1501 | Individuel opstaldning, delvis spaltegulv | 1 | 0,20% |
|                                                                           | 1501 | Individuel opstaldning, fast gulv         | 8 | 0,20% |
|                                                                           | 1501 | Løsgående, dybstrøelse + spaltegulv       | 4 | 0,39% |
|                                                                           | 1501 | Løsgående, dybstrøelse + fast gulv        | 5 | 0,39% |
|                                                                           | 1501 | Løsgående, dybstrøelse                    | 6 | 1,00% |
|                                                                           | 1501 | Løsgående, delvis spaltegulv              | 7 | 0,20% |
| 1 årsso m. 32,2 grise til 6,7 kg, 30% andel fra farestald.                |      |                                           |   |       |
|                                                                           | 1502 | Kassestier, delvis spaltegulv             | 1 | 0,20% |
|                                                                           | 1502 | Kassestier, fuldspaltegulv                | 2 | 0,20% |
|                                                                           | 1502 | Friland                                   | 5 | 0,40% |
| 1 producerede smågrise, fra 6,7 til 31 kg                                 |      |                                           |   |       |
|                                                                           | 1511 | toklimastald, delvis spaltegulv           | 1 | 0,20% |
|                                                                           | 1511 | Drænet gulv + spalter (50/50)             | 3 | 0,20% |
|                                                                           | 1511 | fast gulv                                 | 4 | 0,20% |
|                                                                           | 1511 | dybstrøelse                               | 5 | 1,00% |





*N<sub>2</sub>O-emissionen ganges med antallet af dyr pr staldtype og omregnes til CO<sub>2</sub>-ækvivalenter*
### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = N_2O_{stald} \cdot \frac{44}{28} \cdot \theta_{N_2O-CO_2} $$

Hvor: 

•	$\theta$ N<sub>2</sub>O-CO<sub>2</sub></sub> (Omregningsfaktor N<sub>2</sub>O til CO<sub>2</sub>) = 298