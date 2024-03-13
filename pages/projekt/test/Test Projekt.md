---
Title: Test Projekt
Subtitle: Test Projekt
Date: 2024-03-11T14:26:25+01:00
Modified: 2024-03-13T21:02
Slug: projekt/test/eduid
Status: published
Contact: zacharias-tornblom
Category: test
Authors: 
Lang: sv
Translation: false
---

`passmenu` is a [dmenu][]-based interface to [pass][], the standard Unix
password manager. This design allows you to quickly copy a password to the
clipboard without having to open up a terminal window if you don't already have
one open. If `--type` is specified, the password is typed using [xdotool][]
instead of copied to the clipboard.

On wayland [dmenu-wl][] is used to replace dmenu and [ydotool][] to replace xdotool.
Note that the latter requires access to the [uinput][] device, so you'll probably
need to add an extra udev rule or similar to give certain non-root users permission.


iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii
