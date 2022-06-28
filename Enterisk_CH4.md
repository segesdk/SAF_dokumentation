# **Enterisk metan på grisen**

### **Beregning:**

**Beregning af enterisk metan for slagtegrise/FRATS** 

$$CH_{4_{enterisk}} = \frac{(V_{slagt} \cdot \Delta_d - V_{ind}) \cdot Fe \cdot {F} \cdot Ym}{\theta_{MJ-CH_4}} $$

**Beregning af enterisk metan for smågrise** 

$$CH_{4_{enterisk}} = \frac{(V_{afgang} - V_{ind}) \cdot Fe \cdot {F} \cdot Ym}{\theta_{MJ-CH_4}} $$

**Beregning af enterisk metan for årssøer** 

$$CH_{4_{enterisk}} = \frac{SF \cdot {F} \cdot Ym}{\theta_{MJ-CH_4}} $$

Hvor: 

* V<sub>slagt</sub> (Slagtevægt) = input fra bruger el. standard fra regneark: [Slagtevægt konv. & FRATS](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!B105&action=embedview) / [Slagtevægt øko](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27%C3%98ko.-Inddata%27!B42&action=embedview)
* Δ<sub>d</sub> = 1,31
* V<sub>afgang</sub> (Afgangsvægt) = input fra bruger el. standard fra regneark: [Afgangsvægt konv](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!B67&action=embedview) / [Afgangsvægt øko](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27%C3%98ko.-Inddata%27!B28&action=embedview)
* V<sub>ind</sub> (Indsættelsesvægt) = input fra bruger el. standard fra regneark: [Slagtegris konv](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!B104&action=embedview) / [FRATS](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!A140&action=embedview) / [Slagtegris øko](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27%C3%98ko.-Inddata%27!B41&action=embedview) / [Smågris konv](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!B66&action=embedview) / [Smågris øko](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27%C3%98ko.-Inddata%27!B27&action=embedview)
* Fe (FEsv pr kg tilvækst) = input fra bruger el. standard fra regneark: [Fesv/kg tilvækst](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C14&action=embedview)
* F (foder, MJ pr foderenhed) = Input fra foderberegning el. standard fra regneark: [Foder MJ pr foderenhed](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C7&action=embedview)
* SF (sofoder pr årsso) = Input fra foderberegning el. standard fra regneark: [Sofoder konv](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!B13&action=embedview) / [Sofoder øko](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27%C3%98ko.-Inddata%27!B13&action=embedview)
* Ym-faktor [Ses i regnearket](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C5&action=embedview)
* $\theta$<sub>MJ-CH<sub>4</sub></sub>   (Omregningsfaktor MJ til CH<sub>4</sub>) [Ses i regnearket](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C6&action=embedview)



*CH<sub>4</sub>-emissionen ganges med antallet af dyr pr staldtype og omregnes til CO<sub>2</sub>-ækvivalenter*
### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = CH_{4_{enterisk}} \cdot \theta_{CH_4-CO_2} $$

Hvor: 

•	$\theta$<sub>CH<sub>4</sub>-CO<sub>2</sub></sub>(Omregningsfaktor CH<sub>4</sub> til CO<sub>2</sub>) [Ses i regnearket](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Enterisk%20metan%2Bsoallokering%27!C3&action=embedview)