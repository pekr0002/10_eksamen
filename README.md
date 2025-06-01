# Sprog:

Alt på engelsk undtagen pages (og README ;))


# Navngivning:

## Generelt
### TitleCase for:
- html/css variabler
- astro

### camelCase for:
- javaScript
- klasser
- id'er
- billeder


## Branches

[hvad man laver] - [navn]
eksempel: *Galleri-Penny*


## Commits

add []
eksempel: *add fonts*


# Filstruktur

## src
Astro-komponenter lægges i "components"-undermappen
Sitets undersider lægges i "pages"-undermappen
Generel CSS lægges i "styles"-undermappen
Layout.astro ligger i "layouts"-undermappen

## public
Alle billeder læggesi "public"-mappen. Billeder som bruges på flere sider, så som logo, favicon og Lillemand, lægges direkte i "public", men billeder som kun bruges på en side, lægges i en mappe med sidens navn. Eksempel: billeder til index lægger i "indexPage"-undermappen. 

# Syntax

## REM
Angiv font-size i .rem værdier og gør det samme i alle elementer som skal ændre størrelse proportionelt med skriftens. 
