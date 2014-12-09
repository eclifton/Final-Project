Final-Project
=============
SoundStudio is a LabView program for recording mono-channel audio, combining tracks, and playing the recordings back using a DAQ-
driven microphone and speaker. It relies on the "Record," "AdvancedMixing," and "Playback" sub vi's for recording, mixing, and 
playback respectively. The DAQ assistants are configured to use analog input 0 and analog output 0. Audio signals are stored as 
binary waveforms.

The Recording tab allows the user to define a length of time in seconds to record. The file path should be left blank to create a
new file, or you can select an existing file to overwrite. Pressing Start begins the recording. Once the determined time has
elapsed, the waveform of the track appears in the tab.

The Mixing tab has volume controls for each of two tracks to be mixed. Select two recorded audio files as Track 1 and Track 2.
They need not be the same length. The user can also define start times for each track. A period of silence will be added at the
beginning of the track. When the tracks are mixed, a period of silence is also automatically added to the end of the shorter track
to make the lengths match. Leave the output file path blank to create a new file, or select an existing file to overwrite. 
Pressing Start mixes the tracks. The waveforms of the three tracks can be viewed after the operation is performed.

The Playback tab reads audio files and plays them using DAQ hardware. Choose a file to play and select a volume setting
appropriate to the speaker used. When Start is pressed the track will play on repeat until stopped.

Included are example audio files of an a'capella rendition of Daft Punk's One More Time. "Drums," "Bass," and "Lead" are the raw
vocal recordings. "Drums and Lead" is an intermediate mix. "Final Mix" is the mix of all three tracks. "Voice" is a recording of
the original vocal track and "One More Time" is a mix of "Final Mix" and "Voice."
