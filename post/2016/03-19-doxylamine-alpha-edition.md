---
layout:     post
title:      Doxylamine Alpha Edition
date:       2016-03-19 22:30 +0100
author:     Croydon
summary:    We released version 0.6.0 aka Doxylamine Alpha Edition.
---

We released recently our next version named __Doxylamine Alpha Edition__.

The new release brings, for instance, an improved version of Ambient Occlusion. Ambient Occlusion shadows are now anti-aliased. Furthermore, Ambient Occlusion is now opt-in for new maps, instead of opt-out. 

In addition to that, we have readded the old masterserver with a few adjustments as a temporary solution. More improvements regarding servers includes, for example, that players with a modified map are getting spectated (toggleable in the settings), a command line option to use another path for the config file, and the server command *mapmode -map- -mode-*.

On top of that, we are starting our Node.js integration now by default with the client and [we decided to start with an implementation](https://github.com/inexor-game/code/pull/291) of a web server + UI all over again.

We also fixed a potential crash, if one is trying to load a map with non-existing textures. 

Windows users can, as always, download the latest release [from GitHub](https://github.com/inexor-game/code/releases).

Please test Inexor, report us bugs and give us feedback. Your feedback can have an huge impact on the development of the game. Do not miss this chance. 

The full changelog can be found [here](https://github.com/inexor-game/code/blob/master/changelog.md#doxylamine-alpha-edition-v060-alpha-2016-03-06).