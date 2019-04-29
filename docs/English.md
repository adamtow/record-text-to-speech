# Record Text to Speech
Make audio recordings of Siri speaking inputted text.

> [**Download Record Text to Speech from RoutineHub &raquo;**](https://routineHub.co/shortcut/2506)

<span id="overview"></span>
## Overview

## Table of Contents

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Download and Installation](#download)
- [Getting Started](#getting-started)
- [Interface](#interface)
- [Editing Recordings](#editing-recordings)
- [Settings](#settings)
- [Errors](#errors)
- [Framework](#framework)
- [Localization](#localization)
- [Version History](#version-history)
- [License](#license)

***

<span id="system-requirements"></span>
## System Requirements
Record Text to Speech requires:

- iOS 12 or higher
- Shortcuts 2.2 or higher

Shortcuts also requires access to your Photos library, when your text to speech recordings are temporarily saved to.

***

<span id="download"></span>
## Download and Installation
Download the latest version from RoutineHub.co:

- [**Download Record Text to Speech from RoutineHub**](https://routinehub.co/shortcut/2506)

### Adding Screen Recording to Control Center
Record Text to Speech works best when you can easily access Screen Recording from Control Center. If Screen Recording is not in your Control Center, perform the following steps to add it:

1. From the iOS Home Screen, tap **Settings**.
2. Tap **Control Center**.
3. Tap **Customize Controls**.
4. Tap **+** next to Screen Recording.

To access Control Center, swipe up from the Home Button if your iOS device has a Home button. Otherwise, swipe down from the top-left of the screen, usually where the battery indicator is located. 

The Screen Recording Icon looks like a circle with a solid white filled circle in the middle. 

***

<span id="getting-started"></span>
## Creating Your Text to Speech Recording
Let's create your first text to speech recording.

1. From the Record Text to Speech home screen, tap **New Recording…**.
2. Enter the text you want to have spoken.
3. If Display Hints is enabled, instructions will appear on screen. Tap OK to dismiss the alert.
4. Choose the language of your inputted text.
5. Activate Screen Recording from Control Center.
6. Wait three seconds until the red Screen Recording icon appears in the status bar of your iOS device.
7. Tap Done.
8. Shortcuts will now speak your text.
9. When Shortcuts has finished speaking, additional instructions will appear in an alert.
10. Tap the red Screen Recording icon in the status bar. 
11. Tap Stop to stop the screen recording. Wait for the notification from iOS that the recording has been saved to Photos before proceeding to the next step. 
12. Tap OK to dismiss the instructional alert.

Next, a menu will appear with the following commands to perform on the text to speech recording:

- **Play**: Play the audio recording.
- **Quick Look**: Display a Quick Look interface for the audio recording.
- **Trim Audio**: Display an editing window so you can trim the beginning and end of the audio clip.
- **Record Again**: Discard the current recording and re-enter the text to be spoken and recorded.
- **Save Audio**: Save the current audio recording to the Record Text to Speech folder in `iCloud Drive/Shortcuts`.
- **Don't Save**: Discard the current recording and return to the Record Text to Speech Home screen.

In the cases of Record Again, Save Audio, and Don't Save, Photos will prompt you to delete the Screen Recording that was recorded. Files are saved in the `iCloud Drive/Shortcuts/Record Text to Speech` folder, so you don't need the screen recording in Photos anymore.


***

<span id="interface"></span>
## Exploring the Record Text to Speech Interface
When you open to the Record Text to Speech Home screen, you're presented with the following sections of information:

- **New Recording**: Create a new text to speech audio recording.
- **Recordings**: Display a list of recent recordings that you have previously recorded. Recordings are sorted by creation date. 
- **Show All Recordings**: Tap to display more recordings that you have recorded.
- **About**: Display the About screen with the version and build number.
- **Help**: Display the documentation you are reading now.
- **Settings**: Adjust settings for the shortcut.

***

<span id="editing-recordings"></span>
## Editing Recordings
Tap on a recording from the Recode Text to Speech Home screen to edit it.

- **Play**: Play the audio recording.
- **Quick Look**: Display a Quick Look interface for the audio recording.
- **Trim Audio**: Display an editing window so you can trim the beginning and end of the audio clip.
- **Delete Audio**: Delete the current audio recording from the `iCloud Drive/Shortcuts/Record Text to Speech` folder.
- **Back**: Returns to the Return Text to Speech Home screen.

***

<span id="settings"></span> 
## Settings
Tap Settings from the Home screen to edit Record Text to Speech's settings.

- **Show All Recordings at Startup**: Display all recordings when Record Text to Speech starts up. By default, the shortcut will display the last 10 recordings.
- **Display Hints**: Show instructions before displaying the Speak Text action dialog.
- **Check for Updates Automatically**: Check for updates when Record Text to Speech launches.
- **Number of Recordings to Display**: If Show All Recordings at Startup is disabled, this preference allows you to set the number of recent recordings that will be displayed T launch. 
- **Check for Updates**: Manually check for updates to the shortcut.
- **Change Language**: Change the language for the shortcut.
- **Back to Home**: Return to the Record Text to Speech Home screen.

*** 

<span id="errors"></span>
## Handling Errors
If you forget to start or end recording the Screen Recording, an error dialog will appear when you tap Done. You'll have to re-record the text in order to save the recording.

*** 

<span id="framework"></span>
### App Framework
Record Text to Speech was developed using the [Shortcut App Framework](https://routinehub.co/shortcut/1510) approach to developing application-like shortcuts. This framework was also used to develop:

- [**Cronios**](https://routinehub.co/shortcut/1267): The shortcuts scheduler for iOS.
- [**GeoCuts**](https://routinehub.co/shortcut/1732): Run shortcuts automatically based on your location.
- [**WatchCuts**](https://routinehub.co/shortcut/1864): Trigger shortcuts on your iPhone and iPad using any of your iCloud-connected devices: iPhone, iPad, Mac, Apple Watch, or iCloud.com!
- [**LaunchCuts**](https://routinehub.co/shortcut/959): Folders and tags for your organizing and launching your shortcuts.
- [**Inspector**](https://routinehub.co/shortcut/1106): View and modify objects at runtime in your shortcuts.

Learn more how you can create your own [shortcut applications with App Framework here](https://tow.com/shortcuts/framework).

*** 

<span id="localization"></span> 
## Localization
Record Text to Speech is available in English, but the application is fully ready to be localized. I have developed an application, Localization Helper, that will assist you in localizing Record Text to Speech into your language.

> [**Download Localization Helper from RoutineHub &raquo;**](https://routinehub.co/shortcut/1931)

When the localization file is complete, either submit a pull request on [my GitHub page](https://github.com/adamtow/).

***

<span id="version-history"></span>
## Version History

- 1.0.0: Released April 26, 2019. Initial release.
- 2.0.0: Released April 28, 2019. Rewrote using App Framework and using Screen Recording.

***

<span id="license"></span>
## License
Copyright (c) 2019 Adam Tow • tow.com • @atow

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT  SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
