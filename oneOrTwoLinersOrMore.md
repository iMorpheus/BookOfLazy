# Automate. AUTOMATE. AUTOMATE!

~~~~~~~~~~~~~~~~~~~~~~~~~~ Visit this, open that app, play this, edit this....~~~~~~~~~~~~~~~~~~~~~~~~~~
## .bash_profile
- alias DST='open http://destinytracker.com/destiny/query/ps/EyeMorph ;
open http://guardian.gg/en/profile/2/EyeMorph/5' *Need to check my gaming stats.*
- alias iT='open -a iTunes' *Self-explanatory: Open iTunes.*
- alias AP='afplay -t 60' *Via the audio player - afplay() play the first 60 seconds of {audioTrack}. I don't have to leave the Terminal.app to identify what an audio file contains.*
- alias SourceBash='source ~/.bash_profile' *My scripts/alias are error-ridden missives to the computer. Lots of SOURCEing required. Can't be bothered typing in the file name every five minutes.*
- alias EditBash='pico ~/.bash_profile'   *Early on, it was necessary for me to edit my profile page every thirty seconds.*
- alias YTD='youtube-dl' *Passes url to youtube-dl for downloading. NOTE: Might add -f mp4 to avoid the occassional .webm download.*
- alias bin='cd ~/bin/ ; clear ; ls -FC' *Ugh, what was the name of that script/directory?*


## Scripts/Functions: Work and podcast related.
- mp32m4a.sh: *Convert .mp3 files to .m4a via afconvert*
- T2S.sh (Text to Speech): *Directs say() to convert selected text file into an audio file.*
- wav2m4a.sh (.wav to .m4a): *Directs afconvert() to convert .wav to .m4a.*
- StatsGen.sh (Stats Generator): *Generates number of downloads for each episode of Death by Horror*
- DK_INV.sh: *Generates listening content in male/female en_GB, en_AU & en_US voices for my students.*

## OS X Services
- SpeakJapanese: Reads selected Japanese text in the Otoya T2S voice. Why? Because I'm illiterate in Japanese.
