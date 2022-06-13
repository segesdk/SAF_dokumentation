# **Ammoniak (NH3) på grisestalden**

### **Beregning:**

**Beregning af fordampning, kg NH3<sub>N</sub> per svin stald** 

$$ NH3_{stald} = TAN_N \cdot Tab_{NH3Stald} \cdot VS $$

Hvor: 

 * Tab<sub>NH3Stald</sub> ses i tabellen nederst
 * VS: Effekten af evt. valgte virkemidler på stalden


**Beregning af kg TAN<sub>N</sub> ab slagtesvin** 

$$ TAN_N = \frac{\frac{T \cdot F \cdot R \cdot K}{P}-T \cdot N}{1000}$$

Hvor: 

Tilvæksten, T, beregnes:
$$ T = (S  \cdot \Delta_d) - I $$

og
 * F: Fesv pr kg tilvækst = Indtastning el std. 2,65
 * R: Råprotein g pr foderenhed = se KLI-282
 * K: FordøjelighedsKoefficient = 0,81
 * P: Protein til N = 6,25
 * N: N pr kg tilvækst = 29,6
 * S: Slagtevægt = input fra landmanden el standard (se SAFK-24)
 * Δ<sub>d</sub> = 1,31
 * I: Indsættelsesvægt = input fra landmanden el standard (se SAFK-24)


 
|Dyretype C_2004|Kode dyretype C_2029|Staldtype C2005|Kode staldsystem C_2030|Tab<sub>NH3Stald</sub>: Indirekte N2O tab i stalden, % af N ab dyr|
|---|---|---|---|---|
|1 producerede slagtesvin,| | | | |
| |1512|delvis spaltegulv med 50-75 % fast gulv|7|0,2%|
| |1512|delvis spaltegulv med 25-49 % fast gulv |8|0,2%|
| |1512|drænet gulv + spalter (33/67)|3|0,2%|
| |1512|fast gulv |4|0,2%|
| |1512|Dybstrøelse, opdelt lejeareal |5|0,37%|
| |1512|Dybstrøelse|6|1%|
|1 produceret FRATS, kon.| | | | | 
| |1520|Delvis spaltegulv med 50-75% fast gulv|2|0,2%|
| |1520|Delvis spaltegulv med 25-49% fast gulv|3|0,2%|
| |1520|Drænet gulv + spalter (33/67)|4|0,2%|
| |1520|Fast gulv|5|0,2%|
| |1520|Dybstrøelse, opdelt lejeareal|6|0,37%|
| |1520|Dybstrøelse|7|1%|
|1 producerede slagtesvin, økologiske| | | | | 
| |1516|Udendørs|1|0,4% |
| |1516|Delvis spaltegulv inde. Løbegård (50/50) ude|2|0,2%|
| |1516|Dybstrøelse hele arealet inde. Løbegård med fast/drænet gulv + spaltegulv (50%/50%)|3|0,56%



*N<sub>2</sub>O-emissionen ganges med antallet af dyr pr staldtype og omregnes til CO<sub>2</sub>-ækvivalenter*
### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = NH_{3_{stald}} \cdot \frac{44}{28} \cdot 0,01 \cdot \theta_{N_2O-CO_2} $$

Hvor: 

•	$\theta$ N<sub>2</sub>O-CO<sub>2</sub></sub> (Omregningsfaktor N<sub>2</sub>O til CO<sub>2</sub>) = 298