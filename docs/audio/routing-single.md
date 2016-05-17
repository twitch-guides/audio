## Sending your Audio through a DAW

*(DAW: Digital Audio Workstation. Basically a software mixer, audio processor, recorder and many more things)*

This is probably the most flexible way to handle Audio a single computer setup - you can separate audio sources like applications,
games, VoIP applications (Skype, Discord etc.), control if only you or your stream should be able to hear them, process them
in real time and record them separately if needed.

The idea is that you create several virtual Windows audio devices, for example one for games, one for other applications,
whatever you need. Those devices feed into your DAW (along with your microphone) which you can use to control volumes and
whatever else you want to do with the audio. Then you send the audio from there into another virtual Windows audio device
which you can select in OBS/XSplit.

Installing the necessary tools is fairly quick, but you will have to invest some time into learning how to use
the DAW that you will be sending your audio through if you have never used one.

### Installing the tools

1. Make sure you have an ASIO driver. If you have an audio interface or any other (semi-)professional sound card it should have
one, otherwise you will need to use Asio4All. I won't cover how to set up Asio4All here, but it's really not hard.
2. Install [Synchronous Audio Router][SAR]
3. Pick your favorite DAW software and install it.

[SAR]: https://github.com/eiz/SynchronousAudioRouter/releases "Synchronous Audio Router"

