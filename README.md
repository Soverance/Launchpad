Launchpad
=========

An UE4-compatible game launcher

[![Build Status](https://travis-ci.org/Nihlus/Launchpad.svg?branch=master)](https://travis-ci.org/Nihlus/Launchpad)

![Launchpad (GTK# on Linux)](https://i.imgur.com/Xq1mtRl.png "Launchpad (GTK# on Linux)")

Features:

* Self-updating
* Can install, update and verify the game installation
* Basic design (I am not an artist)

Usage guide: https://forums.unrealengine.com/showthread.php?29904-Launchpad-A-free-open-source-UE4-compatible-game-launcher

Note for users installing on Unix - you may need to install some additional libraries for Launchpad to run.
Simply run /Scripts/launchpad-dependencies.sh if your system is Debian or Debian-based, and it'll install them for you.

If you are not on a Debian-based system, you have to install these packages:
* libnotify-cil-dev
* libwebkitgtk-dev

If you are on Windows, you'll also need the GTK# runtime.
http://www.mono-project.com/docs/gui/gtksharp/installer-for-net-framework/

# Code contributors
* Jarl Gullberg
* Mentos
* Neur0t1c
