# Klausimai

Q: Kas yra use case validation
rasau cia

Ats: use case'us turi padengt komponentus, uztenka traceability matricoj
komponetu, JEI komponentai veliau padengia klases.

Q: Ar tinka CICD/Deployment/State/Use Case

Ats: CI/CD tinka
    Deployment reikia pavaizduot azure serverio galimybes (RAM, CPU) ir
    client device irgi ir susiet su komponentais Deployment diagramoj gyvena
    package'ai State diagrama:
        Butinai nurodyt konkretu objekta kuris modeliuojamas.  zaidimu kinda
        good, user state kinda trash
    Use case turi buti validuojami use case esme, kad turi viska surist

Q: Ar prie information model reikia ER diagramos?

Ats: jo reikia ER diagrama

Q: Ka rasyt prie context?

Ats: sistemos tikslai, ka atlieka, tech sprendimai scope paminet: ka darysim
ko ne?  bet labai glaustai

Q: Ar tinka plantuml klasiu visibility notacija?

Ats: arba paminet ka zenkliukai reiskia arba escapint characterius

Notes:
    packages nepadengti testai?  DAUGIAU KOMENTARU prie visko Parasyt prie
    klases diagramos kiek padengia codebase
