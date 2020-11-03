# MS Teams mute microphone with AHK

This is an AutoHotkey script to jump to last opened MS Teams window and mute or unmute microphone, using Media Pause button/event. 

Media Pause is available as a shortcut on many keyboards and Bluetooth headphones (eg. Bose, Sony etc).

After starting the script an icon should be in the tray, green icon when script is active, red when it's deactived. 

When script is active a press on Media Pause button (or any other way to get the event) will jump to MS Teams, and mute/unmute microphone. If there is no active meeting it should just jump to MS Teams. When deactivated, the Media Pause button resumes its normal function.

Note: needs AutoHotKey, tested and made with 1.1.33 (Available as ZIP on AutoHotKey website).

Note 2: you can AHK compile it. Don't use compression when compiling as most antivirus software detects it as malware.

Reason for this script:<br />
I'm often in some long meetings in MS Teams, where I'm needed only for a few minutes (or even less). I have several screens, and while MS Teams is active in one screen I continue my work on other screens. But when it's my turn to talk, I often scramble to find my mouse and to click the unmute button, or at least click in the MS Teams window to press CTRL-SHIFT-m , which is the mute/unmute microphone combination.
I use Bose QC 35 II Bluetooth headphones which have a multifunction button which is used for playing and pausing music (Media Pause event). As I cannot listen to music and the meeting (in Teams), and the button is righte there on the headphones, I decided to use the Media Pause button as the shortcut for muting and unmuting my microphone. 

Note 3: I am aware that pressing Volume + and - at the same time can mute the microphone on the QC35II, but it's not supported in all software and it expects more dexterity than this solution.

