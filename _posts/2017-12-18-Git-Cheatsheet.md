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
<ul>
<li>git config --global user.email NAME@EMAIL.TLD</li>
<li>git config --global user.name NAME</li>
</ul>
</td>
</tr>
<tr>
<td markdown="span">**Repo klonen**</td>
<td markdown="span">git clone URL</td>
</tr>
<tr>
<td markdown="span">**Upstream hinzufügen und aktualisieren**</td>
<td markdown="span">
<ul>
<li>git remote add upstream URL</li>
<li>git fetch Upstream</li>
<li>git rebase upstream/master</li>
</ul>
</td>
</tr>
<tr>
<td markdown="span">**Branch erzeugen**</td>
<td markdown="span">git checkout -b BRANCHNAME</td>
</tr>
<tr>
<td markdown="span">**Änderungen committen**</td>
<td markdown="span">
<ul>
<li>git add GEÄNDERTEDATEIEN</li>
<li>git commit -m "AUSSAGEKRÄFTIGE COMMITMESSAGE"</li>
</ul>
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
