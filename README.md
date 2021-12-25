# AudioVideo-Streamer

This allows you to stream audio and video from android 10+ phone to windows 7/8/10/11.

### Prerequisites

What things you need to install the software and how to install them

`You need to have VLC and some default .NET runtimes. If you're using windows N edition you have to install this: `https://support.microsoft.com/en-us/topic/media-feature-pack-list-for-windows-n-editions-c1c6fffa-d052-8338-7a79-a4bb980a700a

### Installing

1. `Download newest release`
2. `Unrar with 7zip/winrar or other program`
3. `Connect your phone to computer and enable debugging in developers options NOTE: While connecting your phone have to be unlocked.`
4. `Run "TeslaAudioVideo Streamer.exe"`

### Known Issues
Issue with permissions:
```
java.lang.SecurityException: uid 2000 does not have android.permission.MANAGE_APP_OPS_MODES.
```
> Solution:
In Developer options, scroll to bottom and enable `Disable Permission Monitoring`.

No sound: 
> Solution:
You need to run the program without the audio input on the phone turned on. You also need to run the program with an unlocked phone.
