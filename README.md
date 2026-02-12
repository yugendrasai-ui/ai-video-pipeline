# AI Video Generation Pipeline

This project is an automated system that generates YouTube-ready videos from a single topic input using free AI tools.

One trigger runs the full pipeline: script generation, voice creation, image fetching, and video rendering.

---

## Features
- AI script generation (Google Gemini)
- Text-to-speech (Edge TTS)
- Image fetching (Pexels API)
- Video creation (MoviePy)
- Fully automated workflow

---

## Workflow

Topic → Script → Voice → Images → Video (MP4)

---

## Tech Stack
- Python
- Google Gemini API
- Edge TTS
- Pexels API
- MoviePy
- Google Colab

---

## Usage
1. Open the notebook in Google Colab.
2. Add GEMINI_API_KEY and PEXELS_KEY in Secrets.
3. Run all cells.
4. Enter a topic.
5. Get final_video.mp4.

---

## Future Improvements
- Subtitles
- Thumbnails
- YouTube upload

---

## Author
Ugendra Sai
