# Chroma Discord App (Unofficial)

Enable `Chroma` lighting in the `Discord App for Windows`

## Table of Contents

* [See Also](#see-also)
* [Releases](#releases)
* [Dependencies](#dependencies)
* [Quick Start](#quick-start)
* [Discord Events](#discord-events)
* [Overview](#overview)

## See Also

* [CChromaEditor](https://github.com/RazerOfficial/CChromaEditor) - Editor for editing Chroma animations

* [ChromaTwitchExtension](https://github.com/tgraupmann/ChromaTwitchExtension) - Adds Chroma lighting to the Twitch streaming experience

## Releases

* [Chroma Discord App (Unofficial) Installer](https://github.com/tgraupmann/ChromaDiscordApp/releases/tag/1.0) for Windows

## Dependencies

* [Razer Synapse](https://www.razerzone.com/synapse) - Control `Chroma` application priority

* [Razer Chroma SDK](http://developer.razerzone.com/works-with-chroma/download/) - Allow applications to control `Chroma` lighting. The `ChromaSDK` is automatically installed by `Synapse` when a `Chroma` device is connected.

* [Discord App for Windows](https://discordapp.com/) - The `Discord` client handles authentication

## Quick Start

* Install `Synpase`

* Install `ChromaSDK`

* Install and run `Discord App for Windows`

* Install and run `Chroma Discord App (Unofficial)`

![image_2](images/image_2.png)

* Check `Connect to Discord Events`

![image_9](images/image_9.png)

* Authorize `Chroma` to interact with `Discord` events.

![image_6](images/image_6.png)

## Discord Events

Chroma lighting animations will play for the following Discord events.

** Waiting for authorization **

![image_13](images/image_13.gif)

<hr/>

** Authorization successful **

![image_14](images/image_14.gif)

<hr/>

** Waiting for messages **

![image_15](images/image_15.gif)

<hr/>

** A message has arrived **

![image_16](images/image_16.gif)

<hr/>

** Joined a voice channel **

![image_17](images/image_17.gif)

<hr/>

** Left a voice channel **

![image_18](images/image_18.gif)

<hr/>

** An error occurred **

![image_19](images/image_19.gif)

<hr/>

## Overview

Use `Synapse` to control the `Chroma` app priority. The `topmost` entry will take priority when multiple `Chroma` sessions are active.

![image_7](images/image_7.png)

The application keeps an icon in the system tray with a context menu to either `show` or `quit` the application.

![image_1](images/image_1.png)

When `Launch at Startup` is checked, the application will launch when the user logs into Windows.

![image_8](images/image_8.png)

When `Connect to Discord Events` is checked, `Chroma` animations will play when `Discord` events are detected. The `Discord App` will prompt for authentication when checked for the first time.

![image_9](images/image_9.png)

Also when `Connect to Discord Events` is checked, the `Chroma` animations cannot be customized.

![image_4](images/image_4.png)

Uncheck `Connect to Discord Events` to customize `Chroma` animations.

![image_10](images/image_10.png)

Select a `Discord Notifications` event which will autoplay the selected animation on connected `Chroma` devices.

![image_5](images/image_5.png)

Select a `Chroma` device icon in order to customize the selected animation for that device.

![image_3](images/image_3.png)

The animation editor will appear when editing a `Chroma` animation.

![image_11](images/image_11.png)

Use the device `Reset` button to reset a `Chroma` animation back to the default for the selected `Discord` event.

![image_12](images/image_12.png)
