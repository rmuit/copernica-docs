# Click registratie (oude stijl) in de Publisher

Elke klik op een link in de berichten verstuurd met de publisher wordt 
opgeslagen in een "pom-clicks-old" log file. In Publisher wordt het 
onderscheid gemaakt tussen clicks die geregistreerd zijn door het oude 
of nieuwe tracking syteem. In het artikel 
[nieuwe tracking systeem](https://www.copernica.com/nl/blog/post/nieuw-link-tracking-systeem "Nieuw link tracking systeem") 
kun je meer lezen over de verschillen tussen de twee systemen. 
De inhoud van de "pom-clicks-old" logfiles kun je downloaden in 
CSV, JSON en XML formaat, zie "Meer informatie over logfiles" voor 
instructies van het opvragen hiervan. De logfiles bevatten de volgende 
eigenschappen per klik:

| Data         | Omschrijving                                      |
| ------------ | ------------------------------------------------- |
| id           | ID van het geklikte bericht                       |
| senderdomain | Domein van de verzender                           |
| time         | Tijdstip van de click                             |
| ip           | IP adres van de klikker                           |
| header       | Header van de request van de klik                 |
| email        | Email van de oorspronkelijke ontvanger            |
| tags         | Tags van het bericht, gescheiden door puntkomma's |
| countrycode  | Code van het land waarin geklikt werd             |
| countryname  | Naam van het land waarin geklikt werd             |
| regioncode   | Code van de regio waarin geklikt werd             |
| city         | Naam van de stad waarin geklikt werd              |
| profile      | ID van het profiel van de ontvanger               |
| subprofile   | ID van het subprofiel van de ontvanger            |
| template     | ID van het gebruikte template                     |

## Andere logfiles

* [Marketing suite algemeen log](./rest-cdm-attempts-logfile)
* [Marketing suite misbruik log](./rest-cdm-abuse-logfile)
* [Marketing suite click log](./rest-cdm-click-logfile)
* [Marketing suite ontvangst log](./rest-cdm-delivery-logfile)
* [Marketing suite error log](./rest-cdm-error-logfile)
* [Marketing suite impressies log](./rest-cdm-impression-logfile)
* [Marketing suite herzendingen log](./rest-cdm-retry-logfile)
* [Marketing suite uitschrijvingen log](./rest-cdm-unsubscribe-logfile)
* [Publisher algemeen log](./rest-pom-attempts-logfile)
* [Publisher misbruik log](./rest-pom-abuse-logfile)
* [Publisher clicks (nieuwe stijl) log](./rest-pom-clicks-logfile)
* [Publisher ontvangst log](./rest-pom-delivery-logfile)
* [Publisher error log](./rest-pom-error-logfile)
* [Publisher impressies log](./rest-pom-impression-logfile)
* [Publisher herzendingen log](./rest-pom-retry-logfile)
* [Publisher uitschrijvingen log](./rest-pom-unsubscribe-logfile)

## Meer informatie over logfiles

* [Overzicht van alle API calls](rest-api)
* [Vraag namen van logfiles op](rest-get-logfiles-names)
* [Een logfile downloaden in JSON formaat](./rest-get-logfiles-json.md)
* [Een logfile downloaden in CSV formaat](./rest-get-logfiles-csv.md)
* [Een logfile downloaden in XML formaat](./rest-get-logfiles-xml.md)
