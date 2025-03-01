# Lydhistorier i app baseret på specifikke lokationer i Vejle

## Koncept
App hvor man kan gå rundt i vejle og lytte til specielle lydklip der passer til specielle områder i Vejle. Lydklippene er mellem 0,5 og 2,5 minutter lange. 

## Arbejde
App med sider
 * Hver side har en beskrivelse og et lydklip
 * Man skal kunne starte og stoppe et lydklip, og evt spole tilbage til start
 * Hver side relaterer sig til et område i Vejle (Med adresse?)
 * Hver side har en 'næste knap' og 'tilbage knap'
Startside
 * Beskrivelse 
 * Kom Igang knap
Slutside
 * Afslutningsbeskrivelse 

### MVPer
0. Opsætning: Angular, Capacitor, Kirby (20 timer)
1. POC: Afspil lydklip, udgiv på android og angular (20 timer)
2. MVP 1: Med sider, lydklip, beskrivelser, startside, slutside, evt "om" side (20 timer)
3. MVP 2: Med kort, markers og klik-event på markers (20 timer)
4. MVP 3: Mod gps-navigation på kort (15 timer)
5. MVP 4: Ved tilnærmelse af marker skal tilhørende side dukke frem (15 timer)
6. Udgivelse: Udgiv på Android, udgiv på IOS (10 timer) 

### Udgivelse
* Lille app -> opsætning + POC + MVP1 + Udgivelse (70 timer)
* Mellem app -> + MVP 2 (90 timer)
* Stor app -> + MVP 3 (105 timer)
* Stor app+ -> MVP 4 (120 timer)

### Plan
Aflever 1 måned før til test og integration med rigtig lydklip
* Test Audio
* Test Kort
