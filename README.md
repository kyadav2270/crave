# 🎈 CRAVE

A 9:16 hand-tracking game for Instagram Reels / YouTube Shorts. Catch food (Zomato red) and groceries (Blinkit yellow) with your hands. Build your haul. Hit a tier. Record and share.

**Play:** [https://kyadav2270.github.io/crave/](https://kyadav2270.github.io/crave/)
**Live stats:** [https://kyadav2270.github.io/crave/stats.html](https://kyadav2270.github.io/crave/stats.html)

## How to play
1. Allow camera when prompted
2. Pick a mode (∞ Free / 60s / 30s)
3. Hit **▶ Start** — countdown begins
4. Use your hands to catch falling items, avoid imposters
5. Hit **⏺ Record** to save a video, then **⬇ Download** when done

## Tech
- 1080×1920 canvas, MP4 export with audio (Chrome) or WebM fallback
- MediaPipe Hands for gesture tracking (works with built-in webcam, or iPhone via Continuity Camera)
- All logic in a single self-contained `index.html`
