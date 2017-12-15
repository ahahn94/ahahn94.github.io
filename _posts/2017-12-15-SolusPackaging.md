---
layout: post
title: "Pakete, Podcasts und Programme"
date: 2017-12-15 19:00:00 +0200
categories: Allgemein
---
In den letzten 2 Wochen ist einiges passiert.  

## Pakete packen für Solus
Ich habe angefangen, Pakete im <a href="https://github.com/solus-project/3rd-party">3rd Party Repo</a> von Solus zu aktualisieren.  
Außerdem habe ich auch noch das UML-Modelierungswerkzeug <a href="https://www.modelio.org/">Modelio</a> für das normale Repo aus den Quellen paketiert.  

## Gastautor und -podcaster bei NerdZoom.de
Über das Aktualisieren von Paketen im 3rd Party Repo habe ich einen <a href="https://www.nerdzoom.de/mein-erster-pull-request-bei-solus/">Gastbeitrag bei NerdZoom</a> verfasst.  
Außerdem war ich <a href="https://www.nerdzoom.de/nerdzoom-podcast-folge-2-niemand-hat-die-absicht-ueber-technik-zu-reden/">im NerdZoom-Podcast zu Gast</a> und habe mit Marius über das Bauen von Paketen und allerlei anderes geschwatzt.  
<!--more-->

## Neue Software von mir

### AudioBookConverter
Der AudioBookConverter ist ein Java-Konsolenprogramm, das mit Hilfe von FFmpeg aus M4A-Dateien MP3-Dateien macht.  
Klingt erst einmal nicht sehr spektakulär. Der Kniff dabei ist folgender:  
Das Programm teilt die M4A-Datei anhand der Kapitelmarken in einzelne MP3-Dateien, die auch schon korrekt getaggt sind.  

So kann man z.B. einen mehrere Stunden langen Podcast wesentlich bequemer per USB-Stick im Auto hören, da man so gut zwischen den Kapiteln navigieren kann.  

Zur Zeit arbeite ich noch an einem AudioBookConverter-Snap. Der ist so weit fertig, ich muss ihn allerdings noch in den Snap Store bekommen.  

Den AudioBookConverter gibt es <a href="https://github.com/ahahn94/AudioBookConverter">hier</a>.  

### autoripFlac
Mit autoripFlac kann man CDs automatisch in das FLAC-Format rippen lassen, sobald eine Audio CD eingelegt wird.  
Das Programm unterstützt mehrere Laufwerke und holt sich automatisch die Metadaten zur CD aus dem Internet.  
Den größten Teil der Arbeit macht dabei das Programm abcde ("A Better CD Encoder").  
Die CD wird nach dem Einlesen automatisch ausgeworfen. So kann man auch größere Mengen CDs schnell digitalisieren.  
Das FLAC-Format bietet sich dabei besonders an, da man so auch gleich eine unkomprimierte Version der Tracks als Backup ablegen kann.  
So kann einem dann auch eine zerkratzte CD nicht mehr viel anhaben, da man in Zukunft für das Konvertieren in andere Formate oder Qualitäten einfach das Backup verwenden kann.  

autoripFlac gibt es <a href="https://github.com/ahahn94/autoripFLAC">hier</a>.
