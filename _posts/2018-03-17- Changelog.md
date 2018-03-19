---
title: Changelog
author:
layout: section
---

<font size="6" color="#000000">0.7</font>
Split screenshot into smaller parts and created a layout for them in order to increase visibility and readability<br>
A cycled screenshot will no longer be taken when using the alt+ tab key combination<br>
Changed the key for priming the cycled screenshots to angled brackets (Left of Z; right of Shift)<br>
Added functionality for disconnecting a specific player<br>
Added "Prime" command to CLI so that any user can prime any other users cycled screenshots<br>
Fixed a bug where a faulty cycled screenshot could be taken if tab was pressed more than two times before the screenshot could be taken<br>
Fixed a memory leak that would occur if a split screenshot failed<br>

<font size="6" color="#000000">0.6</font>
Added disconnection handling<br>
Added protection against mistimed screenshots<br>
Added disconnect and quit CLI commands<br>
Moved image handling to its own thread in order to avoid stalls<br>
Newly connected clients will now always receive the images of all relayed clients<br>
CLI command input is now case insensitive<br>
Fixed a crash that would occur if an invalid IPv4 address was supplied to the connect command<br>

<font size="6" color="#000000">0.5</font>
Minimal viable product version.
Can be used to synchronize screenshots between four clients.