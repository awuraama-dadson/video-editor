# Audiogram Studio

Turn an audio file into a shareable video. Upload a podcast episode or any recording, add cover art and a title, and export a video with an animated waveform that moves with the sound. Ready for YouTube, Instagram, TikTok and anywhere else that takes video.

Everything runs in the browser. Your audio and images never leave your device.

## Features

- **Audio to video** from MP3, WAV, M4A and other common audio formats
- **Cover art** with a blurred, colour-matched background, or show initials if there's no image
- **Three formats**: 16:9 (YouTube), 1:1 (square posts) and 9:16 (Shorts, Reels, TikTok)
- **Three waveform styles**: bars, wave and a ring around the cover
- **Custom colours** for the accent and background
- **Clip export**: set a start and end time to cut a short highlight
- **Live preview** with play, pause and seek before you export
- **1080p output** at 30 fps

## How to use

1. Choose an audio file and, if you like, a cover image.
2. Enter the show name and episode title.
3. Pick a format, waveform style and colours.
4. Optionally set a clip start and end, such as `1:30` and `2:45`.
5. Click **Export video** and wait for it to finish.
6. Click **Download** to save the video.

## Good to know

- **Export runs in real time.** A 10-minute clip takes 10 minutes to record. Keep the tab open and visible until it finishes, or the video may freeze.
- **File type depends on the browser.** Safari and recent versions of Chrome save MP4. Other browsers save WebM, which YouTube also accepts.
- **Desktop works best.** On phones, a long export can stop if the screen locks or you switch apps. On iPhone, downloaded videos are saved to the Files app.

## Running locally

There's no build step and nothing to install. Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploying

The site is a single static page, so it works on any static host. On Vercel, import the repository and deploy with the default settings.

## Built with

Plain HTML, CSS and JavaScript, using the Canvas, Web Audio and MediaRecorder browser APIs.
