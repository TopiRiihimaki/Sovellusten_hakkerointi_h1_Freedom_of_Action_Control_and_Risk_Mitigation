ISMS piiriini kuuluu:
-	Windows-kannettava, jota käytän kurssilla
-	Docker Desktop ja sen kautta käytettävä Ubuntu-ympäristö
-	Oma kotireititin ja Wi-Fi-verkko
-	Kotiverkossa oleva tulostin
-	Oma puhelin, jota käytän MFA:han
-	Kurssiin liittyvät tiedot ja materiaalit
-	Kurssiin liittyvät käyttäjätunnukset, salasanat sekä MFA-tiedot
-	OneDrive ja Github

Asiat jotka EIVÄT kuulu omaan ISMS piiriini:
-	Muiden perheenjäsenten tietokoneet
-	Muiden perheenjäsenten puhelimet
-	Muut heidän käyttämänsä laitteet
-	Internet-palveluntarjoajan oma infrastruktuuri
Syitä miksi nämä ovat ISMS:n ulkopuolella:
-	Minulla ei ole pääsyä/oikeuksia niihin
-	En hallinnoi niitä
-	Internet-palveluntarjoajan oma infrastruktuuri, koska se on oman kotiverkkoni ulkopuolella enkä voi hallita tai ylläpitää sitä.

Oman ISMS-ympäristöni keskeinen raja sijaitsee kotiverkon ja internetin välillä. Kotiverkkoon kuuluvat oma reititin, Wi-Fi-verkko ja siihen yhdistetyt omat laitteet. Reititin toimii rajapintana oman kotiverkon ja internetin välillä. Kotiverkosta muodostetaan yhteyksiä ulkopuolisiin pilvipalveluihin, kuten OneDriveen ja GitHubiin. Näiden palveluiden ja ympäristöjen ylläpito ei kuulu omaan hallintaani. Internet-yhteyden osalta rajapintana toimii oma reititin ja sen palomuuri.

Visualisoitu:

<img width="267" height="359" alt="image" src="https://github.com/user-attachments/assets/c55fac61-4288-4705-879e-48ceade45eb2" />
<p></p>


**Sidosryhmä 1**.: Minä itse

Tarve: Kurssitietojen ja -tehtävien säilyminen sekä harjoittelun jatkuvuus.

ISO 27001 -viite: Suunnittelu/Toiminta.

Todiste: Varmuuskopiointiasetukset, OneDriveen tallennetut tiedostot sekä kurssiin liittyvät GitHub-repositoriot.

**Sidosryhmä 2.**: Perheenjäsenet

Tarve: Yksityisyyden säilyminen sekä se, että opiskeluun käytettävä ympäristö ei häiritse muiden perheenjäsenten normaalia verkon ja laitteiden käyttöä.

ISO 27001 -viite: Toimintaympäristö/Toiminta.

Todiste: Dokumentoitu ISMS soveltamisala, jossa muiden perheenjäsenten laitteet on rajattu ulkopuolelle, sekä kotireitittimen ja Wi-Fi:n asetukset.

**Sidosryhmä 3.**: Oppilaitos

Tarve: Kurssin harjoitusten vastuullinen suorittaminen ja se, ettei opiskelijan toiminta aiheuta haittaa muille järjestelmille tai verkoille.

ISO 27001 -viite: Suunnittelu/Toiminta.

Todiste: Kurssin ohjeiden noudattaminen, sekä dokumentointi.

**Sidosryhmä 4.**: Pilvipalveluiden tarjoajat

Tarve: Käyttäjätilien turvallisuus, asianmukainen palveluiden käyttö ja käyttöehtojen noudattaminen.

ISO 27001 -viite: Parantaminen/Toiminta.

Todiste: MFA käyttö sekä tilien turvallisuusasetukset

**Tekoälyn käyttö (ChatGPT):**

- Auttanut ideoimaan

- Auttanut selittämään käsitteitä

- Tehnyt tekstistä helppolukuisempaa
