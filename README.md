Så här lägger du till nya inlägg framöver:
1.	Gå till posts/ mappen i ditt repo
2.	Klicka Add file → Create new file
3.	Skriv filnamn: 2025-12-04-mitt-nya-inlägg/index.qmd
4.	Lägg till innehåll:

yaml
---
title: "Min titel"
author: "Ditt Namn"
date: "2025-12-04"
categories: [kategori1, kategori2]
description: "Kort beskrivning"
---

##Innehåll här

Skriv ditt blogginlägg...
5.	Commit → GitHub bygger automatiskt → Live på några minuter
Tips för framtiden:
•	Lägg till bilder: Släpp bildfiler i samma mapp som index.qmd, referera med ![](bild.jpg)
•	Ändra tema: Redigera _quarto.yml och byt theme: cosmo till andra teman (flatly, darkly, etc.)
•	Lägg till fler sidor: Skapa nya .qmd filer i roten (t.ex. kontakt.qmd)

