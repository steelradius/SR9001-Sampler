THIS PROJECT IS A WORK IN PROGRESS

How to use:
  1. Install plugdata as you would any standard VST plugin
  2. Download this repo and unpack the zip wherever you like
  3. Open plugdata in your DAW of choice, or run it in standalone mode
  4. Click the menu button -> Open Patch -> select the sr9001-sampler.pd patch from this repo
  5. Load an audio file by clicking the "Load Sample" button
  6. Ensure dsp option (bottom right corner) is checked
  7. Set the volume slider to an appropriate level
  8. Press keys on your computer keyboard, MIDI keyboard, or onscreen keyboard to replay the sample.

You can change the sample start and end positions by using their respective sliders.

Functionality as of 10/19/25:
  1. Loading WAV/AIFF/AAC/OPUS/OGG/MP3/FLAC
  2. Sample playback with relative pitch per note
  3. Setting sample start and endpoint (if end position is before start, playback is reversed)
  4. Sample slicing with 8 individual slices available
  5. ADSR envelope
  6. Sample Rate Reduction
  7. Monophonic retrigger voice
  8. Stereo support, mono plays in left channel only
