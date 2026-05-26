# توازن قدرت

```mermaid
flowchart TD

Parliament[مجلس]
Mehestan[مهستان]
King[شاه]
Court[دادگاه قانون اساسی]
Judiciary[قوه قضاییه]
Government[دولت]

Parliament --> Government

Mehestan --> Parliament

Court --> Parliament
Court --> Mehestan
Court --> Government

King --> Court

Judiciary --> Government
Judiciary --> Parliament
```
