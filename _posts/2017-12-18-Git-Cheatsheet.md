---
layout: post
title: "Git Cheatsheet"
date: 2017-12-18 15:00:00 +0200
categories: Allgemein
---
Im Folgenden habe ich eine Liste der von mir besonders häufig genutzten Git-Befehl zusammengestellt.  
<!--more-->
### User konfigurieren
`git config --global user.email NAME@EMAIL.TLD`  
`git config --global user.name NAME`  

### Repo klonen
`git clone URL`  

### Uptream hinzufügen
`git remote add upstream URL`  
`git fetch upstream`  
`git rebase upstream/master`  

### Branch erzeugen
`git checkout -b BRANCHNAME`  

### Änderungen committen
`git add GEÄNDERTEDATEINAMEN`  
`git commit -m "AUSSAGEKRÄFTIGE COMMITMESSAGE"`  

### Änderungen pushen
`git push origin BRANCHNAME`  

### Branch löschen
`git branch -d BRANCHNAME`  
