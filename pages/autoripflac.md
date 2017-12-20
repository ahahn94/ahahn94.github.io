---
layout: page
title: "AutoripFlac"
published: true
permalink: autoripflac.html
---
## About
AutoripFLAC is an automatic audio cd to flac ripper with support for multiple devices.  

## Install  
### Dependencies
- abcde
- libflac

### Install Instructions
Just run these commands:  
`git clone https://github.com/ahahn94/autoripFLAC`  
`cd autoripFLAC`  
`./install.sh `  
Then, set AutoripFLAC as the default application for audio cds.  

### Remove Instructions
To remove run `./remove.sh`.

## Usage
The system will tell the program which device to use and start the ripping process automatically after an audio CD has been detected in the drive.   
The program will not work if called directly from the command line.  
Ripped CDs will be stored under `~/Ripping/`.  
The CD will be ejected after the ripping process has finished.  

### <a href="https://github.com/ahahn94/autoripFLAC">Download</a>
