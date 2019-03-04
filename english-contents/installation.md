# Installation

### Installation Guide

To help your installation, we've prepared an installation video. 

### FileZila

FTP uses FileZila. FileZila is a free program. [Download](https://filezilla-project.org/download.php?type=client)

## Install File Download

* Please download the file via [http://start.xpressengine.io/latest.zip](http://start.xpressengine.io/latest.zip)
* Extract the downloaded zip file and upload it to the server. It will be about 100MB.

## Directory Permission

Set permissions that the Web server can create files.

> When setting permissions, make sure to check Go to sub directory and Apply to all files and directories.

### 1. bootstrap/cache, config/production, storage

Grant 707 permission to these directories

## Launch Web Installer

You accessed the site that you want to install, will be directed to the Install page.

## A known problem

### FTP's file upload error

This may be caused by a missing FTP file upload. in order to resolve, you must upload again. We recommend uploading to the Skip Duplicate File option because similar errors can continue to occur when uploading the same criteria.

### Web server timeout

Depending on the performance of the server, the installation might fail due to the Web server timeout setting.This is a very complex issue that requires changing web server settings.

