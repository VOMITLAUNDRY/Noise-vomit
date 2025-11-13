# Sounds Directory

This directory is where you should place your audio files for the Noise Vomit soundboard.

## Supported Formats

- MP3 (recommended for best compatibility)
- WAV (higher quality, larger file size)
- OGG (good compression, wide support)
- M4A (Apple devices)

## Guidelines

1. **Keep files short**: 1-10 seconds is ideal for a soundboard
2. **Normalize audio levels**: Ensure all sounds have similar volume
3. **Use descriptive names**: e.g., `01-cymbal-crash.mp3`, `02-laser-zap.wav`
4. **Optimize file size**: Compress audio files to reduce loading time
5. **Test on mobile**: Ensure sounds work on mobile devices

## Recommended Audio Settings

- **Sample Rate**: 44.1 kHz or 48 kHz
- **Bit Rate**: 128-192 kbps for MP3 (good balance of quality and size)
- **Channels**: Mono or Stereo (mono preferred for smaller file size)
- **Peak Normalization**: -1 dB to -3 dB to prevent clipping

## Example File Structure

```
sounds/
├── 01-beep.mp3
├── 02-noise.mp3
├── 03-thump.mp3
├── 04-spark.wav
├── 05-pop.mp3
├── 06-whoosh.mp3
└── ...
```

## After Adding Files

Don't forget to update the `sounds` array in `index.html` to include your new audio files:

```javascript
const sounds = [
  "sounds/01-beep.mp3",
  "sounds/02-noise.mp3",
  "sounds/03-thump.mp3",
  "sounds/04-spark.wav",
  "sounds/05-pop.mp3",
  // Add your new files here
];
```

## Tools for Audio Editing

- **Audacity** (Free, Open Source): https://www.audacityteam.org/
- **Ocenaudio** (Free): https://www.ocenaudio.com/
- **Adobe Audition** (Paid): Professional audio editing

## Free Sound Resources

- **Freesound.org**: https://freesound.org/ (Creative Commons sounds)
- **Zapsplat**: https://www.zapsplat.com/ (Free sound effects)
- **BBC Sound Effects**: https://sound-effects.bbcrewind.co.uk/ (Free for personal use)

Remember to respect copyright and licensing when using sounds from external sources!
