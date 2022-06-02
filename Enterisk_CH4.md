# **Enterisk metan på grisen**

### **Beregning:**

$$CH_{4_{enterisk}} = \frac{(S \cdot 1,31 - I) \cdot F \cdot {SF} \cdot Ym}{\theta_{MJ-CH_4}} $$

Hvor: 

* S (Slagtevægt) = input fra bruger el. standard fra tabel
* I (Indsættelsesvægt) = input fra bruger el. standard fra tabel
* F (FEsv pr kg tilvækst) = input fra bruger el. standard fra tabel
* SF (Slagtegrisefoder, MJ pr foderenhed) = 17,3 
* Ym-faktor = 0,006
* $\theta$ <sub>MJ-CH<sub>4</sub></sub> (Omregningsfaktor MJ til CH<sub>4</sub>) = 55,65

*Standardtal:*

| Dyregruppe | Slagtevægt, kg | Indsættelsesvægt, kg | FEsv/kg tilvækst |
|---|---|---|---|
|Slagtegris, konv.|88|30|2,65|
|FRATS, konv.|88|6,6|2,45|
|Slagtegris øko|88|30|2,89|
|Smågris|-|6,4|1,82|
|Smågris øko|-|14|2,25|

*CH<sub>4</sub>-emissionen ganges med antallet af dyr pr staldtype og omregnes til CO<sub>2</sub>-ækvivalenter*
### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = CH_{4_{enterisk}} \cdot \theta_{CH_4-CO_2} $$

Hvor: 

•	$\theta$ <sub>CH<sub>4</sub>-CO<sub>2</sub></sub> (Omregningsfaktor CH<sub>4</sub> til CO<sub>2</sub>) = 25