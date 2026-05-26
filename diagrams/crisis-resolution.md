# حل بحران

```mermaid
flowchart TD

Conflict[اختلاف نهادی]

Mediation[درخواست میانجی‌گری]

King[شاه]

Meetings[جلسات مذاکره]

Agreement[توافق]
NoAgreement[عدم توافق]

Emergency[وضعیت حقوقی ویژه]

Court[دادگاه قانون اساسی]

Decision[رأی نهایی]

Conflict --> Mediation
Mediation --> King
King --> Meetings

Meetings --> Agreement
Meetings --> NoAgreement

NoAgreement --> Emergency
Emergency --> Court
Court --> Decision
```
