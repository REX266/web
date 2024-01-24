---
title: sa-mp.cfg
description: sa-mp client configuration file.
---

## Description

`sa-mp.cfg` is a client configuration file which allows you to change settings related to SA-MP. This file is found in your 'My Documents\\GTA San Andreas User Files\\SAMP' folder, under your Windows user account. This file can be edited with a text editor such as notepad.  

## Options

| Option              | Description                                                                                                                                                                                                                                                                                                                                 |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **pagesize**        | This allows players to set the number of lines displayed in the chat window. It may be set between 10 and 20 lines. The default is 10 lines. This option can be set in-game using the client-side /pagesize command.                                                                                                                        |
| **fpslimit**        | This allows players to set a specific [FPS](http://en.wikipedia.org/wiki/Frame_rate "http://en.wikipedia.org/wiki/Frame_rate") limit, when the frame limiter option is enabled in the GTA:SA menu. Values accepted are 20 to 90. The default set by SA-MP is 50. This option can be changed in-game with the client-side /fpslimit command. |
| **disableheadmove** | This option controls whether player's heads move in the direction they are looking. 1 disables head movements, 0 enables it. This option can be toggled in-game with the client-side /headmove command.                                                                                                                                     |
| **timestamp**       | This allows players to show a local timestamp at the side of chat messages. 1 enables timestamps, and 0 disables them. This can be toggled in-game using the client-side /timestamp command.                                                                                                                                                |
| **ime**             | This controls whether the chat window input supports Input Method text editing and language switching. 1 enables IME, 0 disables it.                                                                                                                                                                                                        |
| **multicore**       | Toggle whether the SA-MP client uses multiple CPU cores when running. Default is 1 (DOES use multiple CPU cores). Set to 0 if you experience mouse problems.                                                                                                                                                                                |
| **directmode**      | This allows players with chat text drawing problems to use the slower direct-to-screen text rendering mode. 0 to disable, 1 to enable.                                                                                                                                                                                                      |
| **audiomsgoff**     | If this option is set to 1, no 'Audio Stream: \[URL\]' messages will be displayed in the chat window when the server plays an audio stream. This option can be toggle in-game using the client-side /audiomsg command.                                                                                                                      |
| **audioproxyoff**   | If this option is set to 1, and there is a proxy server set in your Windows Internet Options, the proxy will not be used when playing audio streams in SA-MP.                                                                                                                                                                               |
| **nonametagstatus** | If this option is set to 0, players will see an hourglass icon next to other players' nametags when they are paused. This is enabled (0) by default. This option can be changed in-game using the client-side /nametagstatus command.                                                                                                       |
| **fontface**        | Allows you to change the font of chat, dialogs and the scoreboard. _i.e. fontface="Comic Sans MS"_. Not officially supported, and may cause problems.                                                                                                                                                                                       |
| **fontweight**      | This option toggles whether your chat font is bold or not. **0 = BOLD (default) and 1 = NORMAL.**                                                                                                                                                                                                                                           |