# 🐦🎵 HumBird

Flappy Bird, but you **sing the right note** to fly through the gaps.

## How It Works

- Walls scroll toward you, each with a gap at a specific musical note height (C, D, E, F, G, A, B)
- **Sing or hum** the displayed note to position your bird at the right height
- Wrong note? You hit the wall and get pushed back slightly to adjust
- 10 wall hits = game over
- Pure client-side, runs entirely in the browser using your microphone

## Play

Open `index.html` in a browser — no build step needed.

## Tech

- Vanilla HTML/CSS/JS
- Web Audio API for real-time pitch detection (autocorrelation)
- Mobile-first responsive design
- No dependencies

## License

MIT
