# Romit Sardar Portfolio

A cinematic racing-inspired portfolio built with plain HTML5, CSS3 and vanilla JavaScript.

## Run locally

No build process is required. Open `index.html` directly or use any static server.

Example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Before deployment

1. Replace `assets/images/hero-bg.jpg` with the final high-resolution racing image.
2. Add your resume at `assets/resume/Romit_Sardar_Resume.pdf`.
3. Replace the placeholder LinkedIn/Email/LeetCode links in `index.html`.
4. Replace project GitHub URLs with individual repository URLs where available.
5. Deploy the folder directly to Vercel.

## Stack

- HTML5
- CSS3
- Vanilla JavaScript


## Background video

Set `VIDEO_URL` at the top of `js/script.js` to a **direct video file URL**, for example an HTTPS URL ending in `.mp4` or `.webm`.

The video is fixed behind the entire page, so it remains visible through the Home, About, Projects and Connect sections. The content sections use transparent backgrounds.

For reliable autoplay, the video is configured as `muted`, `autoplay`, `loop` and `playsinline`.
