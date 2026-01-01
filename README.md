# TFM — Predicció de resultats de futbol amb estadística avançada i Machine Learning

**Autor:** Guillem Mata Valligny  
**Universitat:** Universitat Oberta de Catalunya (UOC)  
**Màster:** Màster en Ciència de Dades  

Aquest Treball Final de Màster té com a objectiu aplicar les tècniques apreses al Màster en Ciència de Dades mitjançant el desenvolupament i l’avaluació de models predictius a partir d’estadístiques avançades de futbol professional.

## Objectius
- Predir el resultat del partit (1X2: victòria, empat o derrota) i el nombre total de gols, obtenint les **probabilitats** associades a cada esdeveniment.
- Comparar els models amb les **probabilitats implícites** de les cases d’apostes (derivades de les quotes).
- Identificar discrepàncies per dissenyar estratègies de **value betting** (potencialment rendibles a llarg termini).

## Dades i abast
L’anàlisi es limita a dades històriques de les **últimes vuit temporades** de les **cinc principals lligues d’Europa**, basades en estadística avançada i quotes. Queden fora factors no estrictament estadístics com lesions, fatiga, climatologia o absències.

## Fonts de dades
- **FBref.com:** resultats i estadístiques avançades (obtingudes via *web scraping*).
- **Football-Data.co.uk:** històric de quotes (*odds*) per derivar probabilitats implícites i comparar-les amb les del model.
