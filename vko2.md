---
layout: default
title: Viikko 2
---

# Tehtävä 2

GitHub Actions tarjoaa erinomaisen alustan **Jekyll-sivustojen automatisointiin**, mahdollistaen kehittäjien tehostaa ja yksinkertaistaa koodin päivitysten, sivuston rakennuksen ja julkaisuprosessin hallintaa. Automatisointiprosessi alkaa luomalla `.github/workflows/jekyll.yml` tiedoston projektin GitHub-repositorioon. Tämä määrittelytiedosto sisältää useita askelia: ympäristön valmistelun, riippuvuuksien asennuksen, sivuston rakennuksen ja lopulta sivuston julkaisun.

Esimerkiksi, työnkulku voi käynnistyä kun muutoksia työnnetään päähaaraan, jolloin GitHub Actions suorittaa määritellyt tehtävät automaattisesti—riippuvuuksien asennuksesta (`bundle install`) sivuston rakentamiseen (`bundle exec jekyll build`) ja sen julkaisemiseen GitHub Pagesissa käyttäen `peaceiris/actions-gh-pages` -toimintoa. Tämä kokonaisvaltainen automatisointi vähentää inhimillisen virheen mahdollisuutta ja nopeuttaa julkaisuprosessia.

## CI/CD-putkiston rakentaminen web-sovellukselle

CI/CD-putkiston (Continuous Integration/Continuous Deployment) rakentaminen web-sovellukselle vaatii kattavan valikoiman kehitystyökaluja ja -tekniikoita. Versionhallinnassa **Git**, yhdessä GitHubin kanssa, tarjoaa vankan pohjan koodin säilyttämiseen ja yhteistyöhön. Koodin laadun varmistamiseksi työkalut kuten **ESLint** (JavaScript) tai **Stylelint** (CSS) ovat olennaisia, kun taas **Jest** tai **Mocha** tarjoavat robustin alustan automatisoituun testaukseen. Riippuvuuksien hallinnassa **NPM** tai **Yarn** ovat keskeisessä roolissa, mahdollistaen kirjastojen helpon hallinnan ja version seurannan.

## Konttiteknologiat ja orkestraatiovälineet

Konttiteknologiat, kuten **Docker**, mahdollistavat sovellusten kapseloinnin itsenäisiin ympäristöihin, mikä tehostaa sekä kehitystä että julkaisua eri ympäristöissä. Dockerin lisäksi orkestraatiovälineet, kuten **Kubernetes** tai **Docker Compose**, tuovat lisäarvoa hallitsemalla sovelluskonttien elinkaarta skaalautuvalla ja luotettavalla tavalla. Yhdistämällä nämä työkalut ja tekniikat, kehittäjät voivat rakentaa tehokkaan CI/CD-putkiston, joka automatisoi testauksen, rakentamisen ja julkaisun prosessit, vähentäen manuaalista työtä ja mahdollistaen nopeammat julkaisusyklit.
