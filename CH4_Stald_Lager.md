# **Metan (CH4) på grisestald- og lager**

## **Stald**

### **Beregning af metan på stald** 

$$ CH_{4_{stald}} = VS_{total} \cdot O \cdot B0 \cdot MCF \cdot P \cdot VM_{CH_4Stald}$$

Hvor: 

 * O: Omregningsfaktor fra m3 til kg metan [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!B63&action=embedview)
 * B0: [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!B62&action=embedview)
 * MCF: methane conversion factor [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!U2&action=embedview)
 * VM<sub>CH<sub>4</sub>Stald</sub>: Effekten af evt. valgte virkemidler på stalden [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Virkemidler%20%27!D26&action=embedview)
* P: Produktionsdage [dage/dyr/stald]: 

$$P = SD \cdot f$$

Hvor:
 * f: fordelingsfaktor stald/lager [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!C58&action=embedview)

*NB for staldtyperne "faremark", "friland" og "udendørs" er P = SD*

 ### **Beregning af SD, stalddage pr dyr, afhænger af dyretypen:**

> Slagtegris (konv. + øko) + FRATS

$$SD = \frac{T}{DT} \cdot 1000+10$$

Hvor tilvæksten, T:

$$ T = V_{slagt}  \cdot \Delta_d - V_{ind}$$


> Smågrise (konv. + øko)

$$SD = \frac{T}{DT} \cdot 1000+4$$

Hvor tilvæksten, T:

$$ T = V_{ud} - V_{ind} $$


> Årsso (løbestald + farestald, konv. + øko)

$$SD = 365$$

Hvor:

 * V<sub>slagt</sub>: Slagtevægt = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!K2&action=embedview) [kg]
 * Δ<sub>d</sub> = 1,31
 * V<sub>ind</sub>: Indsættelsesvægt = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!J2&action=embedview) [kg]
* DT: Daglig tilvækst = input fra bruger el. [Tabelværdi konv.](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27konv.-Inddata%27!B69&action=embedview) / [Tabelværdi øko](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27%C3%98ko.-Inddata%27!B30&action=embedview) [g]
 * V<sub>ud</sub>: Vægt ved afgang/salg/fravænning = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!L2&action=embedview) [kg]


 ### **Beregning af VS<sub>total</sub>:**
$$VS_{total} = \frac{VS_{dyr}}{P + (SD - P)}+\frac{VS_{strøelse}}{P + (SD - P)}$$
 ### **Beregning af VS<sub>dyr</sub>, afhænger af dyretypen:**

>Slagtegrise (konv. + øko)  + FRATS + smågrise (konv. + øko)

$$VS_{dyr} = VS_{tør} \cdot \frac{G \cdot 0,25 + U \cdot 0,02}{G + U} \cdot (G + U)$$

Hvor:

 * G: Gødning ab årsso pr gris [kg]:

$$G = {\frac{\frac{T \cdot F}{Fe} \cdot \frac{87}{100} \cdot (1-0,83)}{0,25}}$$

 * U: Urin ab årsso pr gris [kg]:

 $$U =\frac{T \cdot F}{Fe}\cdot \frac{87}{100} \cdot 2$$

 Hvor tilvæksten, T, beregnes for hhv. slagte/FRATSgrise og smågrise:

$$ T_{slagt+FRATS} = V_{slagt}  \cdot \Delta_d - V_{ind}$$

$$ T_{smågris} = V_{ud} - V_{ind} $$

>Årssøer, løbe-og drætighedsstalden, konv + øko 

$$VS_{dyr} = VS_{tør} \cdot \frac{G \cdot 0,25 + U \cdot 0,02}{G + U} \cdot ((G + U) \cdot X_{løb})$$

 Hvor:

 * G: Gødning ab årsso pr gris [kg]:

$$G = \frac{{\frac{F}{Fe} \cdot \frac{87}{100}}\cdot \frac{1-81}{100}}{\frac{30}{100}}$$

 * U: Urin ab årsso pr gris [kg]:

 $$U ={\frac{F}{Fe} \cdot \frac{87}{100}} \cdot 2,5$$


>Årssøer, farestald, konv + øko 

$$VS_{dyr} = VS_{tør} \cdot \frac{G \cdot 0,25 + U \cdot 0,02}{G + U} \cdot ((G + U) \cdot X_{fare})$$

*G og U i farestalden beregnes på samme vis som for årssøerne i løbe-og drægtighedsstalden*


Hvor: 

 * VS<sub>tør</sub>: VS af tørstof [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!C57&action=embedview)
* F: Foder = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!N2&action=embedview) [Fesv pr kg tilvækst/sofoder pr årsso]
 * Fe: Foderenheder = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!I2&action=embedview) [Fesv pr kg foder]
 * X<sub>løb</sub>  = 0,7 for konv / 0,5 for øko
 * X<sub>fare</sub>  = 0,3 for konv / 0,5 for øko


### **Beregning af VS<sub>strøelse</sub>**
$$VS_{strøelse} = H \cdot H_{tør} \cdot (1- A) \cdot VS_{tør}$$

Hvor: 

 * H: halm per dyr [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27hALM-nORM%27!b3&action=embedview) [kg]
 * H<sub>tør</sub>: Tørstof i halm [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27hALM-nORM%27!C653&action=embedview)
 * A: Askeindhold [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27hALM-nORM%27!C66&action=embedview)
 * VS<sub>tør</sub>: VS af tørstof [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27hALM-nORM%27!C67&action=embedview)


### **Omregning til CO<sub>2</sub>e:**
 $$CO_2e = CH_{4_{stald}} \cdot \theta_{CH_4-CO_2} $$

Hvor: 

•	$\theta$<sub>CH<sub>4</sub>-CO<sub>2</sub></sub>: Omregningsfaktor CH<sub>4</sub> til CO<sub>2</sub> [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C3&action=embedview)

____
## **Lager**

### **Beregning af metan på lager**

*NB for staldtyperne "faremark", "friland" og "udendørs" tilføres der ikke noget til lageret og værdien af CH<sub>4</sub><sub>lager</sub> = 0*

$$CH_{4_{lager}} = VS_{total} \cdot O \cdot B0 \cdot MCF \cdot (SD-P) \cdot VM_{CH_4lager} $$

Hvor: 

 * VM<sub>CH<sub>4</sub>lager</sub>: Effekten af evt. valgte virkemidler på lageret [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Virkemidler%20%27!G26&action=embedview)

### **Omregning til CO<sub>2</sub>e:**
 $$CO_2e = CH_{4_{lager}} \cdot \theta_{CH_4-CO_2} $$

Hvor: 

•	$\theta$<sub>CH<sub>4</sub>-CO<sub>2</sub></sub>: Omregningsfaktor CH<sub>4</sub> til CO<sub>2</sub> [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C3&action=embedview)