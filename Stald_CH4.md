# **Metan (CH4) på grisestalden**

## **Beregning:**

### **Beregning af metan på stald** 

$$ CH4_{stald} = VS_{total} \cdot O \cdot B0 \cdot MCF \cdot P \cdot VM_{CH_4Stald}$$

Hvor: 

 * O: Omregningsfaktor fra m3 til kg metan [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!B63&action=embedview)
 * B0: [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!B62&action=embedview)
 * MCF: methane conversion factor [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!U2&action=embedview)
 * VM<sub>CH<sub>4</sub>Stald</sub>: Effekten af evt. valgte virkemidler på stalden [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Virkemidler%20%27!D26&action=embedview)
* P: Produktionsdage/dyr/stald: 

$$P = SD \cdot 0,69$$

 ### **Beregning af SD, stalddage pr dyr, afhænger af dyretypen:**

> *Slagtegris (konv. + øko) + FRATS + smågrise (konv. + øko)*

$$SD = \frac{T}{DT} \cdot 1000+10$$

Hvor tilvæksten, T, beregnes for hhv. slagte/FRATSgrise og smågrise:

$$ T_{slagt+FRATS} = V_{slagt}  \cdot \Delta_d - V_{ind}$$

$$ T_{smågris} = V_{afgang} - V_{ind} $$


> *Årsso (løbestald + farestald, konv. + øko)*

$$SD = 365$$

Hvor:

 * V<sub>slagt</sub> (Slagtevægt) = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!K2&action=embedview)
 * Δ<sub>d</sub> = 1,31
 * V<sub>ind</sub> (Indsættelsesvægt) = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!J2&action=embedview)
* DT (daglig tilvækst) = input fra bruger el. RETTES [RET](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!J2&action=embedview)
 * V<sub>afgang</sub>: vægt ved salg/fravænning = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!L2&action=embedview)


 ### **Beregning af VS<sub>total</sub>:**
$$VS_{total} = \frac{VS_{dyr}}{P + (SD - P)}+\frac{VS_{strøelse}}{P + (SD - P)}$$
 ### **Beregning af VS<sub>dyr</sub>, afhænger af dyretypen:**

>*Slagtegrise (konv. + øko)  + FRATS + smågrise (konv. + øko)*

$$VS_{dyr} = VS_{tør} \cdot \frac{G \cdot 0,25 + U \cdot 0,02}{G + U} \cdot (G + U)$$

 * G, Gødning ab årsso pr gris (kg):

$$G = {\frac{\frac{T \cdot Fe}{FEF} \cdot 0,87 \cdot (1-0,83)}{0,25}}$$

 * U, Urin ab årsso pr gris (kg):

 $$U =\frac{T \cdot Fe}{FEF }\cdot 0,87 \cdot 2$$

 Hvor tilvæksten, T, beregnes for hhv. slagte/FRATSgrise og smågrise:

$$ T_{slagt+FRATS} = V_{slagt}  \cdot \Delta_d - V_{ind}$$

$$ T_{smågris} = V_{afgang} - V_{ind} $$

>*Årssøer*

MANGLER

Hvor: 

 * VS<sub>tør</sub>: VS af tørstof [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!C57&action=embedview)
 * FEF: Foderenheder pr kg foder = input fra bruger el. [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!I2&action=embedview)


### **Beregning af VS<sub>strøelse</sub>**
$$VS_{strøelse} = H \cdot H_{tør} \cdot (1- A) \cdot VS_{tør}$$

Hvor: 

 * H: kg halm per dyr [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler%20NH3%20og%20N2O%20-Stald%201%27!I2&action=embedview)
 * H<sub>tør</sub>: Tørstof i halm [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!C55&action=embedview)
 * A: Askeindhold [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!C56&action=embedview)
 * VS<sub>tør</sub>: VS af tørstof [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Formler-metan-stald%201%27!C57&action=embedview)