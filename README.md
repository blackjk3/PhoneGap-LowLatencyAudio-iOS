PhoneGap-LowLatencyAudio-iOS
============================

Fork of LowLatency Audio for PhoneGap 3+

Original code: Andrew Trice

Maintainer: Jason Kadrmas

## Install the Plugin

### PhoneGap/Cordova >= 3.0
    cordova plugin add git://github.com/blackjk3/PhoneGap-LowLatencyAudio-iOS.git

Then some extra steps need to be done to disable ARC for the plugin's .m files. Follow [those instructions](http://stackoverflow.com/a/6658549/271585) for LowLatencyAudio.m and LowLatencyAudioAsset.m