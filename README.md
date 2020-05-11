# Grainshifter

Grainshifter is a granular looper that allows pitch and time to be modified independently of each other, with the ability to shuffle segments of audio and record live input. 

Grainshifter divides audio clips into 16 segments, each with their own *shift* and *warp* settings. *Shift* allows for re-ordering of segments, leading to rhythmic sub-loops and creative rearrangement of pre-recorded audio. *Warp* is the playback speed of that segment, allowing you to speed up or slow down the audio by 2 or 4 times, without affecting the pitch.

The *track* and *clip* menus provide access to all tracks and clips shown in session view, allowing you to pull a clip from anywhere in your Live Set. These menus will auto populate when you first add the device, but later changes to the number of clips and tracks will need a manual refresh, which can be done by clicking the *track* and *clip* labels.

*Sync* locks playback to Live's transport. Various settings of *warp* easily allow for clips to become longer than the original audio file, but synced playback will keep things in time with the rest of your live set. Or leave things unsynced for explorations in phasing rhythms and melodies.

*Pitch* is a transposition control for the processed audio. Clicking the *pitch* label will switch between absolute pitch and semitone adjustments. Note that the internal granular engine of Grainshifter works best with un-warped audio or warped clips created in your Live Set at the current tempo.  Clips from other projects modified by Live's warp engine and loaded into Grainshifter can lead to strange pitch results, but an easy workaround is to resample clips warped by Live, and to then load the resampled clip into Grainshifter.

Selecting "~ live input ~" in the clips menu will reveal 3 additional controls. *Input* is a gain control for boosting or reducing levels recorded into Grainshifter's internal buffer. *Overdub* determines how much of the previous audio remains on the next write cycle. *Hi pass* is a subtle high pass filter for reducing low-end frequency content up to 1000 Hz, useful for pitch shifting live input without muddying the sound.

Clicking the *sequencer* button will open a secondary window, revealing four sets of *shift* and *warp* control sections, each representing a step in a four stage sequencer. The *shift* and *warp* can sequences can have independent lengths assigned to them, allowing for a 3-step *shift* sequence over a 4-step *warp* sequence, for example.
