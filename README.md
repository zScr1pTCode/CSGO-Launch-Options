# CSGO-Launch-Options
Counter Strike: Global Offensive | Launch Options - Explained..


# CSGO-Launch-Options
In this guide you will learn how to correctly perform the setting and all available launch options in CS:GO, we will highlight handy settings, which are guaranteed to improve your gaming experience and boost CS GO productivity.


//Each launch option should start with - or + sign, commands should be spaced, and it is also forbidden to use brackets - otherwise commands won’t be working.//
//In CS GO a large number of launch options are available, however, the statement, that all options should be obligatory used is wrong. Most of them are useless and not suitable for all computers.//

# Full list of CS:GO Launch Options
-----------------------------------------------------------------
-full (-fullscreen) - The game will start in full screen mode.

-window - The game will start in the regular window. Commands with similar effect: -windowed, -startwindowed, and -sw

-noborder - Game window won’t have edges.

-x 333; -y 333 - CS:GO window position along the axis X or Y.

-w 1920; -h 1080 - Setting up desired CSGO screen resolution.

+cl_showfps 1 - Your FPS will be displayed at the top right corner.

-high - This launch option setting up CS GO (High) process priority.

-nojoy - Switching off joysticks.

-console - Console will open once the game is started.

-language English - Interface language customization for CS GO. In this case, English language is indicated, however, you can use any other language you like.

-threads - Here you should enter the number of cores your processor has, however, the CS:GO specifies the settings your processor has on its own, thus this command is useless.

+r_drawparticles 0 - Launch option that removes particles animation, graphics will get worse, however, performance will improve.

-nod3d9ex1 - Command for switching off Direct3D 9Ex technology. It is worth trying this command, since game performance may be improved as well.

-autoconfig - This command lets you restore settings to deafult.

+exec file name - Launch option that launching the config with game settings (.cfg). The file should be placed in folder "Steam\SteamApps\common\Counter-Strike Global Offensive\csgo\cfg".

+mat_disable_fancy_blending 1 - This command degrades the quality of textures, as a result, the performance is increasing.

-r_emulate_g - OpenGL emulation is working only for Windows, can increase FPS.

-softparticlesdefaultoff - Rendering particles settings for CS:GO.

-nopreload - Cancels models, files and textures pre-loading.

-nohltv - Switches off all GOTV and Source TV opportunities.

-limitvsconst - Limits number of vertex shaders up to 256.

-forcenovsync - Switches off Vsync technology.

+violence_hblood 0 - Command, which eliminates the elements of violence in the game, particularly blood.

+r_dynamic 0 / 1 - Switches on/off dynamic lightning.

# The Best CS GO Launch Options:

# -freq 240 -d3d9ex -novid -no-browser +mat_queue_mode 2 +fps_max 400 +cl_interp_ratio 1 +cl_interp 0.021 -tickrate 128 +cl_cmdrate 128 +cl_updaterate 128 +cl_forcepreload 1


# Explanation:

-freq 240 - Customization of play frequency for CSGO. The possible values are: 60, 75, 120, 144, 165, 240, 265, 285, 360.

-d3d9ex - Command for switching on Direct3D 9Ex technology, unloading processor at 40%, while loading video card. In full screen mode, the game is wrapping and unwrapping much faster with the help of ALT+TAB, the boost in productivity is noticeable.

-novid - After this launch option the game is starting without a splash screen.

-no-browser - Command no longer works for Panorama UI. The browser was switched off in the past, the one you could see when connecting to the user server.

+mat_queue_mode 2 — Very handy command, which is switching on multicore processing, as the result, fps is raising.

+fps max 0 - This command eliminates FPS limitations. We do not recommend using 0 value, since input lag will raise, especially var and sv values. The value should be chosen according to your mean FPS value.

+cl_interp_ratio 1, +cl_interp 0.021 — Interpolation settings. The majority of people are playing with 1 and 0 values, and thus they are feeling uncomfortable when shooting. It seems, that crosshair is reeling and shaking. We recommend you to test settings, such as ratio 1/2 and interp 0.031/0.021.

-tickrate 128 - TickRate setting for your client will be working for your offline servers and game with bots.

+cl_cmdrate 128, +cl_updaterate 128* — The number of updates per second, received and sent on server. In other words, the value should be maximum, namely 128.

+cl_forcepreload 1 - The game is uploading all map files before logging into the server, reducing the load on computer during the match.
-----------------------------------------------------------------
