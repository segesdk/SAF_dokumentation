# **Energi**

### **Beregning af energi på stalden** 

$$ E_{stald} = E_{N} + E_{H} + E_{O} $$

Hvor: 

 * E<sub>N</sub>: Energi fra naturgas, i CO<sub>2</sub>e [kg/m3]
 * E<sub>H</sub>: Energi fra halm, i CO<sub>2</sub>e [kg/kg]
 * E<sub>O</sub>: Energi fra olie, i CO<sub>2</sub>e [kg/L]

### **Beregning af energi fra naturgas, E<sub>N</sub>:** 

$$ E_{N} = \frac{ N \cdot M \cdot K \cdot C}{1000} $$


Hvor: 

 * N: Naturgas pr årsso = input fra bruger [m<sup>3</sup>]
 * M: MJ per enhed = [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!I26&action=embedview) [MJ/m<sup>3</sup>]
 * K: kwh pr MJ pr enhed = [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!J26&action=embedview) [kwh/MJ/m<sup>3</sup>]
 * C: CO<sub>2</sub>e pr kwh = [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!L26&action=embedview) [g/kwh]

### **Beregning af energi fra halm, E<sub>H</sub>:** 

$$ E_{H} = \frac{ H \cdot M \cdot K \cdot C}{1000} $$

Hvor: 

 * H: Halm i halmfyr pr årsso = input fra bruger [kg]
 * M: MJ per enhed = [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!I27&action=embedview) [MJ/kg]
 * K: kwh pr MJ pr enhed = [Standardtal RET](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!J27&action=embedview) [kwh/MJ/kg]
 * C: CO<sub>2</sub> pr kwh = [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!L27&action=embedview) [g/kwh]

 ### **Beregning af energi fra olie, E<sub>O</sub>:** 

$$ E_{O} = \frac{ O \cdot M \cdot K \cdot C}{1000} $$

Hvor: 

 * O: Olie i halmfyr pr årsso  = input fra bruger [L]
 * M: MJ per enhed = [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!I28&action=embedview) [MJ/L]
 * K: kwh pr MJ pr enhed = [Standardtal RET](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!J28&action=embedview) [kwh/MJ/L]
 * C: CO<sub>2</sub> pr kwh = [Standardtal](https://seges.sharepoint.com/:x:/r/sites/SAFprojeketet/_layouts/15/Doc.aspx?sourcedoc=%7B55DC573E-DF3A-4BB4-BA90-49438C005785%7D&file=Formler%20til%20PORK%202.0%20med%20foderberegner.xlsx&activeCell=%27Konv.-Inddata%27!L28&action=embedview) [g/kwh]




