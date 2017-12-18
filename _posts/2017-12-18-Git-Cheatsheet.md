---
layout: post
title: "Git Sheetcheat"
date: 2017-12-18 15:00:00 +0200
categories: Allgemein
---
<table>
<tr>
<td markdown="span">**Git einrichten**</td>
<td markdown="span">
*  git config --global user.email NAME@EMAIL.TLD
*  git config --global user.name NAME
</td>
</tr>
<tr>
<td markdown="span">**Repo klonen**</td>
<td markdown="span">git clone URL</td>
</tr>
<tr>
<td markdown="span">**Upstream hinzufügen und aktualisieren**</td>
<td markdown="span">
*  git remote add upstream URL
*  git fetch Upstream
*  git rebase upstream/master
</td>
</tr>
<tr>
<td markdown="span">**Branch erzeugen**</td>
<td markdown="span">git checkout -b BRANCHNAME</td>
</tr>
<tr>
<td markdown="span">**Änderungen committen**</td>
<td markdown="span">
*  git add GEÄNDERTEDATEIEN
*  git commit -m "AUSSAGEKRÄFTIGE COMMITMESSAGE"
</td>
</tr>
<tr>
<td markdown="span">**Änderungen pushen**</td>
<td markdown="span">git push origin BRANCHNAME</td>
</tr>
<tr>
<td markdown="span">**Branch löschen**</td>
<td markdown="span">git branch -b BRANCHNAME</td>
</tr>
</table>
