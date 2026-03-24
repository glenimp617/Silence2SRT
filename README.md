<p align="center">
  <img src="images/silence2srt-banner.png" width="593">
</p>

# Silence2SRT

Silence2SRT creates an .srt subtitle file from silent or non-silent sections of an audio file. It is useful in video editing applications for quickly placing objects on the timeline as the .srt can be used for marker points.

The team radio graphic at 1:24 in this video was created with the help of Silence2SRT - https://www.youtube.com/watch?v=2LmSJkQ7lCs

https://www.youtube.com/@SimVRRacing

---

## Features

- Opens video or audio files
- Detects available audio tracks and lets the user choose one
- Scans for silent or non-silent sections of audio
- Supports positive or negative timestamp offsets
- Exports timestamps as an `.srt` subtitle file
- Useful for importing markers into video editing software
- Simple desktop interface
- No manual timestamp editing required

---

## Installation

1. Download the latest release from the Releases page
2. Run the application
3. Locate and select `ffmpeg.exe`
4. Select a video or audio file
5. Choose the audio track you want to analyse
6. Select whether to detect silent or non-silent sections
7. Generate the `.srt` output file

`ffmpeg.exe` is required for audio extraction and processing.

---

## Usage

Silence2SRT analyses an audio track and creates an `.srt` subtitle file
containing timestamps for either silent or non-silent sections.

This can then be imported into supported video editing applications
to help place markers or objects on the timeline more quickly.

---

## Compatibility

- Windows 10 / Windows 11
- Video and audio files with supported audio tracks
- `.srt` compatible video editing applications

---

## Known Limitations

- Output accuracy depends on the audio content and detection settings
- Results may vary depending on background noise and audio quality
- Marker import behaviour depends on the target video editing application

---

## License

Silence2SRT is distributed as a binary under a proprietary license.
See LICENSE.txt for details.

---

## Disclaimer

This software is provided as-is without warranty.
Use at your own risk.

---

## Support

Bug reports and feedback are welcome via GitHub Issues.
