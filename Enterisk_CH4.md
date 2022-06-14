# **Enterisk metan på grisen**

### **Beregning:**

**Beregning af enterisk metan for slagtegrise** 

$$CH_{4_{enterisk}} = \frac{(V_{slagt} \cdot \Delta_d - V_{ind}) \cdot Fe \cdot {F} \cdot Ym}{\theta_{MJ-CH_4}} $$

**Beregning af enterisk metan for smågrise** 

$$CH_{4_{enterisk}} = \frac{(V_{afgang} - V_{slagt}) \cdot Fe \cdot {F} \cdot Ym}{\theta_{MJ-CH_4}} $$

**Beregning af enterisk metan for årssøer** 

$$CH_{4_{enterisk}} = \frac{SF \cdot {F} \cdot Ym}{\theta_{MJ-CH_4}} $$

Hvor: 

* V<sub>slagt</sub> (Slagtevægt) = input fra bruger el. standard fra tabel
* Δ<sub>d</sub> = 1,31
* V<sub>afgang</sub> (Afgangsvægt) = input fra bruger el. standard fra tabel
* V<sub>ind</sub> (Indsættelsesvægt) = input fra bruger el. standard fra tabel
* Fe (FEsv pr kg tilvækst) = input fra bruger el. standard fra tabel
* F (foder, MJ pr foderenhed) = Input fra foderberegning el. standard fra tabel
* SF (sofoder pr årsso) = Input fra foderberegning el. standard fra tabel
* Ym-faktor = 0,006
* $\theta$ <sub>MJ-CH<sub>4</sub></sub> (Omregningsfaktor MJ til CH<sub>4</sub>) = 55,65

*Standardtal:*

| Dyregruppe | Slagtevægt, kg | Indsættelsesvægt, kg | FEsv/kg tilvækst | Foder, MJ pr foderenhed | Afgangsvægt, kg | Sofoder pr årsso | 
|---|---|---|---|---| ---| ---|
|Slagtegris, konv.|88|30|2,65| 17,3 | -| -|
|FRATS, konv.|88|6,6|2,45| 17,2 | -| -|
|Slagtegris, øko|88|30|2,89| 17,3 | -| -|
|Smågris|-|6,4|1,82| 16,5 | 30| -|
|Smågris, øko |-|14|2,25| 16,5 | 30| -|
|Årsso, konv. |-|-|-| 17,5 | -| 1516|
|Årsso, øko  |-|-|-| 17,5 | -| 2050|


*CH<sub>4</sub>-emissionen ganges med antallet af dyr pr staldtype og omregnes til CO<sub>2</sub>-ækvivalenter*
### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = CH_{4_{enterisk}} \cdot \theta_{CH_4-CO_2} $$

Hvor: 

•	$\theta$ <sub>CH<sub>4</sub>-CO<sub>2</sub></sub> (Omregningsfaktor CH<sub>4</sub> til CO<sub>2</sub>) = 25