# **Lattergas (N2O) på grisestalden**

### **Beregning:**

**Beregning af lattergas på stald** 

$$N_2O_{stald} = (N_{gris} + N_{strøelse}) \cdot Tab_{N_2OStald} \cdot VM_{N_2OStald} $$

Hvor: 

 * Tab<sub>N2OStald</sub>: Direkte N2O tab i stalden, % af N ab dyr [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!C56&action=embedview)
 * VM<sub>N<sub>2</sub>O</sub><sub>Stald</sub>: Effekten af evt. valgte virkemidler på stalden - *NB der findes pt ingen virkemidler som påvirker N2O i stalden, men kan evt. komme senere*

**Beregning af kg N ab gris, N<sub>gris</sub>, afhænger af dyretypen:** 

*Slagtegris (konv. + øko) + FRATS + smågrise (konv. + øko)* 

$$N_{gris} = \frac{\frac{T \cdot Fe \cdot R}{P}-T \cdot N}{1000}$$

$$ hvor $$

$$ T_{slagt+FRATS} = V_{slagt}  \cdot \Delta_d - V_{ind}$$

$$ og $$

$$ T_{smågris} = V_{salg} - V_{ind} $$

*Årssøer, konv + øko*

OBS: Årssoens klimaaftryk beregnes ved at lægge andelen fra løbe-og drætighedsstalden (X<sub>løb</sub>) sammen med andelen fra farestalden (X<sub>fare</sub>):

$$ \begin{gather*}
N_{gris} = \\
(\frac{\frac{Fe \cdot X_{løb} \cdot R}{1000}}{P} - k_{so} \cdot X_{løb} - \frac{V_{ind} \cdot V_{salg} \cdot N_{pat}}{1000} \cdot X_{løb}) \\
+ \\
(\frac{\frac{Fe \cdot X_{fare} \cdot R}{1000}}{P} - k_{so} \cdot X_{fare} - \frac{V_{ind} \cdot V_{salg} \cdot N_{pat}}{1000} \cdot X_{fare})
\end{gather*}$$



Hvor:
 * Fe: Fesv pr kg tilvækst/sofoder pr årsso = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!N2&action=embedview)
 * R: Råprotein g pr foderenhed = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!O2&action=embedview)
 * P: Protein til N [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!C107&action=embedview)
 * N: N pr kg tilvækst [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!Q2&action=embedview)
 * k<sub>so</sub>: Korrektionsfaktor for soen [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!C112&action=embedview)
 * V<sub>salg</sub>: vægt ved salg/fravænning = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!L2&action=embedview)
 * V<sub>slagt</sub> (Slagtevægt) = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!K2&action=embedview)
 * Δ<sub>d</sub> = 1,31
 * V<sub>ind</sub> (Indsættelsesvægt) = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!J2&action=embedview)
  * X<sub>løb</sub>  = 0,7 for konv / 0,5 for øko
  * X<sub>fare</sub>  = 0,3 for konv / 0,5 for øko
  * N<sub>pat</sub>: N pr kg tilvækst for pattegrisen [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!R2&action=embedview)

**Beregning af kg N fra strøelse**
$$ N_{strøelse} = Halm \cdot Z $$

 * Halm, kg halm per dyr [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!I2&action=embedview)
 * Z: kg N pr. kg strøelse [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!B96&action=embedview)

### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = N_2O_{stald} \cdot \frac{44}{28} \cdot \theta_{N_2O-CO_2} $$

Hvor: 

•	$\theta$ N<sub>2</sub>O-CO<sub>2</sub></sub> (Omregningsfaktor N<sub>2</sub>O til CO<sub>2</sub>) [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C2&action=embedview)