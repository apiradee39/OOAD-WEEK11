# OOAD-WEEK11
State Diagram

รูปที่ 1 taxi
```
@startuml

title Taxi

State Taxi
State Man
State Drive
State "Tell Place" as Tellplace

Man -down-> Call
Call --> Tellplace
Tellplace --> Taxi
Taxi --> Drive
@enduml
```


![]    (http://www.plantuml.com/plantuml/img/HOvB2e0m30NtEKLmtok8e5j1q0i4pQ8GgsZy7D_65jqyPaB2IxKhRNhC0g1UXN6WsmFqIfevOKiXKxFvapCN0ujW9pHoWRIZwMe640_GJSiLN8arYO05kcZ_qaTfRcqMhwKQg3XCyRi7)          



รูปที่ 2 homework
```
@startuml

title Pass Homework

State Homework
State Do
State Me
State Teacher

Teacher -right-> Me
Me -down-> Do
Do -left-> Homework
Homework -up-> Teacher
@enduml
```

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU8goIp9ILK8I2mkLl38pqqjpo_Avk8ABaaiIKNm8LoNV2Z3DnNA24bDJCv8BUBYWZ8KT8ioqpDATEr0IdnJ5NHJyilpW3oWJfTy1TsSr3IG7DnO64D1jxG0A0uppI4rBmNeD000)


รูปที่ 3 Certification Process
```
@startuml
title Certification Process
State "Certification Process" as CertificationProcess{
  State Application
  State "Documentation Review" as DocumentationReview
  State "Assessment Planning" as AssessmentPlanning
  State "Certification Assessment" as CertificationAssessment
  State "Certification Approve" as CertificationApprove
  State "Surveillance Visit" as SurvillanceVisit
  State "Re-certificate Audit" as RecertificateAudit
  Application -down-> DocumentationReview
  DocumentationReview --> AssessmentPlanning
  AssessmentPlanning --> CertificationAssessment
  CertificationAssessment --> CertificationApprove
  CertificationApprove --> SurvillanceVisit
  SurvillanceVisit --> RecertificateAudit
  RecertificateAudit --> Application  
}
@enduml
```
![](http://www.plantuml.com/plantuml/img/TP91QiCm44NtSuh1UryX9BG720vaB-Hf6L0a8usTHUZTAqkk5TSoUFN-lB7qqJc8yZ8-382m6C8Fyi9Vh9MmitZrJbC803THGjXKqmPLs7fBy090pEPb6CmIhgpvT7fya9MyhQE9wPcMROBCYtK98UwUOxmQPItRxoGL_eUBiprtcTmVlMI7zZ1uDr55pK7nRgEVY4qyZIQyS-3ylnalDC4YTDJgTMCiRUmNfQCtdd2KulTMAxQzUzhsT51UXM8RfwkjxM6QFIxg8AbOQqSrdEPhzVn3QQxQoHxcMswU7_m0dCdsyTd_0W00)



รูปที่ 4 Make a Book

```
@startuml

title Make a Book
State Book {
  State "Preparing manuscripts" as Preparingmanuscripts
  State "make a pdf file" as makeapdffile
  State "Make cover and bookmark" as Makecoverandbookmark
  State "Contact printing" as Contactprinting
  State Distribute
  State "Tax filing in the end year" as Taxfilingintheendyear
  Preparingmanuscripts -up-> makeapdffile
  makeapdffile -up-> Makecoverandbookmark
  Makecoverandbookmark -up-> Contactprinting
  Contactprinting -up-> Distribute
  Distribute -up-> Taxfilingintheendyear
 }

@enduml
```
![](http://www.plantuml.com/plantuml/img/TPBDRi8m48JlVeeHTrwXGgLN92Jw0ako52k9OzaRr0hnxgmTGr9-f1ooy-riPgIieb2GeMkD4IijOqCDW_3PzuqnEo7X_8wpWG56OR4Dx2bOzuEEt12hOBt41IZYJcPWydNZSLyVSB0jPqVII9KaJ9ivHjMVE81SZRr6w2WqsP5OHafkO7AkUoTK2Roc40sIBKMyQVVjBnibsFqWiqz_qszAbzfP1paoM1FyCOLyIl58zTIH5IMYRdrUbSToyCkFnvRpiMoyQVLABexdKWzAsVjNSXeAVTldOinAH_qthW00)


รูปที่ 5 Time

```
@startuml
title Time
State year{
State month{
State week{
State day{
State hour{
State minute{
State second{

}

}

}

}

}

}

}

note left of minute : 60 seconds = 1 minute
note right of hour : 60 minutes = 1 hour
note left of day : 24 hours = 1 day
note right of month : 30 days = 1 month
note left of year : 12 months = 1 year
@enduml
```

![](http://www.plantuml.com/plantuml/img/RP1H2i8m38RVUueSOPlYWo3i3dg1uZ9RN5leCcI8TpTjQd4YzA7__tz9slGpwKYBcvGYInF2nJfKwaoQ45RKyVaHBdWoLJqGxrKCUgrt4vQl6kiNmYfdl0O_i7pzEpumCk584CPI2KSuDALiXXEqnHSssfl9S9efgCI29dVRbD_9MBVFaK1i_JJB_sHirwImJ4tUjbVQ3LDj9w5moLIgHp_mHjy0)







