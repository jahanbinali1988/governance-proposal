# ساختار قدرت

```mermaid
flowchart TD

People[مردم]

Parliament[مجلس]
Guilds[شوراهای صنفی]
Mehestan[مهستان]

PM[نخست‌وزیر]

King[شاه]
Court[دادگاه قانون اساسی]
Army[ارتش]

People --> Parliament
People --> Guilds

Guilds --> Mehestan

Parliament --> PM

Parliament --> Court
Mehestan --> Court

King --> Court
King --> Army

Parliament <--> Mehestan
Court --> Parliament
Court --> Mehestan
```
