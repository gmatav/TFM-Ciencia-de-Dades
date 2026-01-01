# Treball de Final de Master
## Master en Ciència de Dades
### Predicció de resultats de futbol amb estadística avançada i Machine Learning

# TFM — Predicció de partits de futbol amb estadística avançada i ML

Aquest Treball Final de Màster té com a objectiu aplicar les tècniques apreses al Màster en Ciència de Dades mitjançant el desenvolupament i l’avaluació de models predictius a partir d’estadístiques avançades de futbol professional.

## Objectius
- Construir models capaços de predir:
  - el resultat del partit (1X2: victòria, empat o derrota),
  - el nombre total de gols,
  obtenint les **probabilitats** associades a cada esdeveniment.
- Comparar el rendiment dels models amb les **probabilitats implícites** de les cases d’apostes (derivades de les quotes).
- Avaluar si els models poden **igualar o superar** les estimacions comercials i identificar discrepàncies per dissenyar estratègies de **value betting** (potencialment rendibles a llarg termini).

## Dades i abast
L’anàlisi es limita a dades històriques de les **últimes vuit temporades** de les **cinc principals lligues d’Europa**, incloent:
- resultats i estadístiques avançades obtingudes via **web scraping**,
- històric de **quotes** publicades per cases d’apostes.

## Fonts de dades
- **FBref.com:** resultats i estadístiques avançades dels partits de futbol professional. Les dades s’han obtingut mitjançant tècniques de *web scraping* i posterior processament per construir el dataset d’anàlisi i modelatge.
- **Football-Data.co.uk:** històric de quotes (*odds*) de cases d’apostes. A partir d’aquestes quotes s’han derivat les probabilitats implícites (i, quan escau, s’ha ajustat el marge o *overround*) per comparar-les amb les probabilitats estimades pels models.

Autor: Guillem Mata Valligny

Universitat Oberta de Catalunya
