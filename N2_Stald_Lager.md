# **Indirekte N<sub>2</sub>0 (N<sub>2</sub>) på grisestald- og lager**

## **Stald**

### **Beregning af indirekte N<sub>2</sub>0 (N<sub>2</sub>) på stald** 

$$ N_{2stald} = TAN_N \cdot Tab_{N_2stald} \cdot VM_{N_2stald} $$

Hvor: 

 * Tab<sub>N<sub>2</sub>stald</sub>: Indirekte N<sub>2</sub>O tab i stalden [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!I56&action=embedview) [% af N ab dyr]
 * VM<sub>N<sub>2</sub>stald</sub>: Effekten af evt. valgte virkemidler på stalden [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Virkemidler%20%27!C26&action=embedview)

### **Beregning af kg TAN<sub>N</sub> ab gris, afhænger af dyretypen:**

>Slagtegris (konv. + øko) + FRATS + smågrise (konv. + øko)  

$$ TAN_N = \frac{\frac{T \cdot F \cdot R \cdot K}{P}-T \cdot N}{1000}$$

Hvor tilvæksten, T, beregnes for hhv. slagte/FRATSgrise og smågrise:

$$ T_{slagt+FRATS} = V_{slagt}  \cdot \Delta_d - V_{ind}$$


$$ T_{smågris} = V_{ud} - V_{ind} $$

>Årssøer, løbe-og drætighedsstalden, konv + øko 

$$TAN_N = (\frac{\frac{F \cdot X_{løb} \cdot R \cdot K}{1000}}{P} - k_{so} \cdot X_{løb} - \frac{(V_{ind} \cdot V_{ud}) \cdot X_{løb} \cdot N_{pat}}{1000})$$

>Årssøer, farestald, konv + øko 

$$TAN_N = (\frac{\frac{F \cdot X_{fare} \cdot R \cdot K}{1000}}{P} - k_{so} \cdot X_{fare} - \frac{(V_{ind} \cdot V_{ud}) \cdot X_{fare} \cdot N_{pat}}{1000})$$



Hvor:
 * F: Foder = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!N2&action=embedview) [FEsv pr kg tilvækst/FEso pr so]
 * R: Råprotein = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!O2&action=embedview) [g pr foderenhed]
 * K: FordøjelighedsKoefficient [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!U2&action=embedview)
 * P: Protein til N [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!C107&action=embedview)
 * N: N i dyret [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!Q2&action=embedview) [g N pr kg tilvækst]
 * k<sub>so</sub>: Korrektionsfaktor for soen [Standardtal konv.](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!C112&action=embedview) / [Standardtal øko](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!C116&action=embedview)
 * V<sub>ud</sub>: Vægt ved afgang/salg/fravænning = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!L2&action=embedview) [kg]
 * V<sub>slagt</sub>: Slagtevægt = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!K2&action=embedview) [kg]
 * Δ<sub>d</sub> = 1,31
 * V<sub>ind</sub>: Indsættelsesvægt = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!J2&action=embedview) [kg]
 * X<sub>løb</sub>  = 0,7 for konv / 0,5 for øko
 * X<sub>fare</sub>  = 0,3 for konv / 0,5 for øko
 * N<sub>pat</sub>: N i pattegrisen [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!R2&action=embedview) [g N pr kg tilvækst]

### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = N_{2stald} \cdot \frac{44}{28} \cdot 0,01 \cdot \theta_{N_2O-CO_2} $$

Hvor: 

 * $\theta$ N<sub>2</sub>O-CO<sub>2</sub></sub>: Omregningsfaktor N<sub>2</sub>O til CO<sub>2</sub> [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C2&action=embedview)

____

## **Lager**

### **Beregning af ammoniak på lager**

*NB for staldtyperne "faremark", "friland" og "udendørs" tilføres der ikke noget til lageret og værdien af N<sub>2lager</sub> = 0*

$$N_{2lager} = (TAN_N - N_{2stald}) \cdot Tab_{N_2lager} \cdot VM_{N_2lager} $$


Hvor: 

 * Tab<sub>N<sub>2</sub>lager</sub>: Indirekte N2O tab på lageret [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!J56&action=embedview) [% af N ab dyr]
 * VM<sub>N<sub>2</sub>lager</sub>: Effekten af evt. valgte virkemidler på lageret [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Virkemidler%20%27!E26&action=embedview)

### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = N_{2lager}  \cdot \frac{44}{28} \cdot 0,01 \cdot \theta_{N_2O-CO_2} $$

Hvor: 

 * $\theta$ N<sub>2</sub>O-CO<sub>2</sub></sub>: Omregningsfaktor N<sub>2</sub>O til CO<sub>2</sub> [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C2&action=embedview)