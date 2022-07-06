# **Lattergas (N2O) på grisestald- og lager**

## **Stald**

### **Beregning af lattergas på stald** 

$$N_2O_{stald} = (N_{gris} + N_{strøelse}) \cdot Tab_{N_2Ostald} \cdot VM_{N_2Ostald} $$

Hvor: 

 * Tab<sub>N<sub>2</sub>Ostald</sub>: Direkte N2O tab i stalden [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!C56&action=embedview) [% af N ab dyr]
 * VM<sub>N<sub>2</sub>O</sub><sub>stald</sub>: Effekten af evt. valgte virkemidler på stalden. *Da disse endnu ikke findes for N2O på stalden ganges blot med 1*

### **Beregning af kg N ab gris, N<sub>gris</sub>, afhænger af dyretypen:** 

>Slagtegris (konv. + øko) + FRATS + smågrise (konv. + øko) 

$$N_{gris} = \frac{\frac{T \cdot F \cdot R}{P}-T \cdot N}{1000}$$

Hvor tilvæksten, T, beregnes for hhv. slagte/FRATSgrise og smågrise:

$$ T_{slagt+FRATS} = V_{slagt}  \cdot \Delta_d - V_{ind}$$

$$ T_{smågris} = V_{ud} - V_{ind} $$

>Årssøer, løbe-og drætighedsstalden, konv + øko 

$$N_{gris} = (\frac{\frac{F \cdot X_{løb} \cdot R}{1000}}{P} - k_{so} \cdot X_{løb} - \frac{V_{ind} \cdot V_{ud} \cdot N_{pat}}{1000} \cdot X_{løb})$$

>Årssøer, farestald, konv + øko 

$$N_{gris} = (\frac{\frac{F \cdot X_{fare} \cdot R}{1000}}{P} - k_{so} \cdot X_{fare} - \frac{V_{ind} \cdot V_{ud} \cdot N_{pat}}{1000} \cdot X_{fare})$$

Hvor:
 * F: Foder = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!N2&action=embedview) [Fesv pr kg tilvækst/sofoder pr årsso]
 * R: Råprotein = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!O2&action=embedview) [g pr foderenhed]
 * P: Protein til N [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!C107&action=embedview)
 * N: N i dyret [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!Q2&action=embedview) [g N pr kg tilvækst]
 * k<sub>so</sub>: Korrektionsfaktor for soen [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!C112&action=embedview)
 * V<sub>ud</sub>: Vægt ved afgang/salg/fravænning = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!L2&action=embedview) [kg]
 * V<sub>slagt</sub>: Slagtevægt = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!K2&action=embedview) [kg]
 * Δ<sub>d</sub> = 1,31
 * V<sub>ind</sub>: Indsættelsesvægt = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!J2&action=embedview) [kg]
  * X<sub>løb</sub>  = 0,7 for konv / 0,5 for øko
  * X<sub>fare</sub>  = 0,3 for konv / 0,5 for øko
  * N<sub>pat</sub>: N i pattegrisen [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!R2&action=embedview) [g N pr kg tilvækst]

### **Beregning af kg N fra strøelse**
$$ N_{strøelse} = H \cdot Z $$

 * H: halm per dyr [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27hALM-nORM%27!b3&action=embedview) [kg]
 * Z: N i strøelse [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!B96&action=embedview) [kg N pr kg strøelse]


### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = N_2O_{stald} \cdot \frac{44}{28} \cdot \theta_{N_2O-CO_2} $$

Hvor: 

•	$\theta$ N<sub>2</sub>O-CO<sub>2</sub></sub>: Omregningsfaktor N<sub>2</sub>O til CO<sub>2</sub> [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C2&action=embedview)

____

## **Lager**

### **Beregning af lattergas på lager**
*NB for staldtyperne "faremark", "friland" og "udendørs" tilføres der ikke noget til lageret og værdien af N<sub>2</sub>O<sub>lager</sub> = 0*

$$N_2O_{lager} = ((N_{gris} + N_{strøelse}) - NH_{3_{stald}} - ((N_{gris} + N_{strøelse}) \cdot VM_{N_2Ostald})) \cdot Tab_{N_2Olager} \cdot VM_{N_2Olager} $$

Hvor: 

 * NH<sub>3stald</sub>: Beregnes i [NH3_Stald_Lager.md](https://github.com/segesdk/SAF_dokumentation/blob/main/N2O_Stald_Lager.md)
 * Tab<sub>N<sub>2</sub>Olager</sub>: Direkte N2O tab på lageret [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-stald%201%27!H56&action=embedview) [% af N ab dyr]
 * VM<sub>N<sub>2</sub>O</sub><sub>lager</sub>: Effekten af evt. valgte virkemidler på lageret [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Virkemidler%20%27!F26&action=embedview)

### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = N_2O_{lager} \cdot \frac{44}{28} \cdot \theta_{N_2O-CO_2} $$

Hvor: 

•	$\theta$ N<sub>2</sub>O-CO<sub>2</sub></sub>: Omregningsfaktor N<sub>2</sub>O til CO<sub>2</sub> [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C2&action=embedview)