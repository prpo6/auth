# Mikrostoritev: Auth

Ta mikrostoritev skrbi za avtentikacijo zaposlenih in članov na front-endu. Omogoča registracijo novih in prijavljanje že obstoječih članov/zaposlenih.

## Zagon

Pred zagonom moramo poskrbeti, da teče PostreSQL baza z že narejenimi tabelami.

Nato v root-u projekta poženemo:
`mvnw spring-boot:run` (na Linux/Mac OS `./mvnw` namesto `mvnw`)¸

Port mikrostoritve, kjer bo MS tekla in konfiguracijo za povezavo in delo z bazo podatkov lahko najdemo v `/auth/src/main/resources/application.properties`