---
layout: post
title: "How to use Migrate on any CUSTOM ROMs"
description: "Instructions on how to use migrate."
categories: [migrate , ROM ,backup]
tags: [ROM, migrate , backup]
redirect_from:
  - /2021/08/29/
---

# Download
Download any of the latest migrate from these links:
 * Stable GPE [Google Playstore Edition](https://play.google.com/store/apps/details?id=balti.migrate&hl=en_IN&referrer=utm_source%3Dgoogle%26utm_medium%3Dorganic%26utm_term%3Dmigrate+google+play+store&pcampaignid=APPU_1_Al-2Xt-qFP2V4-EP-IGdmAs)
 * Beta NG [Non Google Playstore Edition](https://t.me/migrateAppChannel/16)

# Backup
 - Open migrate, take backup of all user apps. Don't take backup of system apps, it can cause bootloop.
 - Take backup of user apps, data & permissions.
 - In next step take backup of call logs, msg, contacts, default keyboard etc. don't mess with what you don't understand.
 - **Backup will be saved in internal storage in migrate folder.**

# Restore
 - To restore this backup - First install ROM than GApps (if needed) than Magisk latest than flash backup zips created in migrate folder in sequence. Don't break this sequence. 
 - When phone boots up, a notification will appear saying "migrate package flashed", click on it to complete restore, if this notification doesn't appear or you by mistake removed this notification, than you can just click on "migrate helper" app (installed when you flashed TWRP migrate package) and complete the restore process.
 - After restore process completes, uninstall or disable migrate helper app. 
