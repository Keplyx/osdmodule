# osdmodule
TeamSpeak 3 (TS3) OSD Module for Linux

Displays an overlay showing your active channel and who is talking. Works along with basically every app.

![screenshot_20180426_212132](https://user-images.githubusercontent.com/23726131/39394772-3a40b8da-4ad6-11e8-92fe-ea748d09ee57.png)

**This was tested on TeamSpeak 3.1.8 (22/01/2018)**

## Prerequisites

It uses dzen2 to produce the overlay window. You can get that by typing (debian style systems):


    sudo apt-get install dzen2


## Installation

Put the files into your /*[ts3]*/plugins/lua_plugin/osdmodule/ folder

The *[ts3]* folder is usually /home/USERNAME/.ts3client

## Activation

Open TeamSpeak3, then to go to **Tools/Options**.

Then select the **Addons** tab

If you haven't already, download and install the **Lua Plugin** (click on 'Browse Online', enter 'lua' and install the plugin). After installation, you may need to restart TeamSpeak3

Now in the **Addons** tab, under **Lua Plugin**, click on **Settings**.

Here, you can uncheck testmodule, then **check osdmodule**.

You may need to reload all, or just restart TS3.

To test it you can type "/lua run osdmodule.test" into the TS3 chat window.

![screenshot_20180426_214615](https://user-images.githubusercontent.com/23726131/39394775-3c92977a-4ad6-11e8-9ebc-cf7796b6e741.png)
