---
title: Backups
description: Backups can save you a lot of headache in case something happens to your installation or device.
lang: en-US
---

# Backups

Backups are inter-compatible between **Aniyomi** versions.

Backups can hold the following information:
1. **Titles**
1. **Categories**
1. **Read/Watched chapters/episodes**
1. **Tracking settings**
1. **Reading/Watching history**
1. **Manga/Anime information** such as Author, Artist, Date Added to Library, Selected Viewer, etc.

::: guide
You can do this by going to <Navigation item="more"/> → <Navigation item="settings_backup"/> and then selecting **Create backup** and select a location to save it.
:::

## How do I restore a backup?

Restoring is done from the <Navigation item="settings_backup"/> settings.

To restore a backup without issues be sure to:

* Log into the <Navigation item="settings_tracking"/> services that you previously used.

To restore a legacy backup without issues be sure to:

* Install all the <Navigation item="tab_extensions"/> that were installed at the time of the backup.
* Log into the <Navigation item="settings_tracking"/> services that you previously used.
* You're able to access all the sources through the **WebView**.
* Be on a consistent internet connection.

## How can I make my new install of Aniyomi detect my old downloads?

You can transfer downloaded manga/anime chapters from one version of **Aniyomi** to another.

::: guide
You can do this by going to <Navigation item="more"/> → <Navigation item="settings"/> → <Navigation item="settings_downloads"/> and then set the download directory to that of the download folder of your old **Aniyomi**, then restore the backup.
:::

## How do I make Aniyomi automatically backup?

It is highly recommended you turn on auto backups, this will ensure you can recover if need be.

::: guide
You can do this by going to <Navigation item="more"/> → <Navigation item="settings_backup"/> and then setting a **backup frequency**. In the case of a catastrophic failure, at least you will be able to recover.
:::