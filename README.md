## Projekts: Spēļu Nejaušinātājs

## Projekta Uzdevums
Šis projekts ir izstrādāts kā noslēguma darbs, kas izmanto Python programmatūras izstrādes prasmes. "Spēļu Nejaušinātājs" ir sistēma, kas automatizē izlasi un attēlošanu spēļu elementiem no populārām spēlēm, piemēram, "Dead by Daylight" un "Valorant". Mērķis ir nodrošināt ērtu un ātru pieeju spēļu elementiem, izcelt izlases varoni vai perku, lai spēlētu izlases raksturu vai vienkāršotu izvēli.

## Tehnoloģijas un Bibliotēkas
- **Python 3**: Izvēlēts tā plašās pielietojamības un atbalstīto bibliotēku klāsta dēļ.
- **Selenium**: Tiek izmantots tīmekļa elementu izgūšanai un mijiedarbībai ar web lapām.
- **Tkinter**: Lietots grafiskā lietotāja saskarnes izveidošanai.
- **Pillow**: Nodrošina attēlu apstrādi un attēlošanu GUI.
- **Openpyxl**: Izmantots, lai strādātu ar Excel datnēm, īpaši datu saglabāšanai un izgūšanai.
- **Requests**: HTTP pieprasījumu apstrādei, lai lejupielādētu attēlus no interneta.

## Programmatūras Izmantošanas Metodes
Projekts sastāv no vairākām galvenajām funkcijām:
1. `fetch_and_display`: Izgūst spēļu elementus un attēlo tos lietotāja saskarnē.
2. `init_valorant_agents_mode`: Inicializē "Valorant Agents" režīmu.
3. `fetch_valorant_agent`: Izgūst informāciju par Valorant aģentiem.
4. `init_mode`: Ļauj lietotājam izvēlēties starp dažādiem spēļu režīmiem.
5. GUI funkcijas: Nodrošina lietotāja mijiedarbību ar programmatūru.

## Izmantošanas Piemēri
Lietotāji var izvēlēties starp dažādiem režīmiem, piemēram, "Survivor", "Killer", vai "Valorant Agents". Katrā režīmā programma nodrošina atbilstošas funkcionalitātes, piemēram, spēļu varoņu vai spēju izgūšanu un attēlošanu. Kā arī ieraksts Excel failā, ziņošanai un atlases tīrībai, kur var redzēt, kas tiek izvadīts pirms tam.