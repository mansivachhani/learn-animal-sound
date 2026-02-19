# Learn Animal Sound

An interactive, kid-friendly web game where children tap animals to hear real animal sounds and play a simple listening challenge.

## Features

- Real animal audio clips (local assets)
- Tap-to-hear animal sounds
- Listening challenge mode (guess the animal from sound)
- Score tracking with stars
- Correct answer celebration:
  - Green check animation
  - Balloon + confetti reward
  - Success tone + clap sound
- Bilingual UI with flag switch:
  - Swedish (default)
  - English
- Mobile-friendly touch interface

## Tech Stack

- Plain HTML, CSS, and JavaScript
- No build tools or framework required

## Project Structure

- `index.html` - complete app (UI + logic)
- `assets/audio/` - animal audio files
- `AUDIO_CREDITS.md` - audio source and license references

## Run Locally

From the project directory:

```bash
cd /Users/denishvachhani/Projects/LetsBuild/learn-animal-sound
python3 -m http.server 8000
```

Open in browser:

- [http://localhost:8000](http://localhost:8000)

Note: using a local HTTP server is recommended for reliable audio playback.

## How To Play

1. Tap any animal card in free play to hear its sound.
2. Tap `Next Sound` to start a challenge round.
3. Listen and tap the matching animal.
4. Tap `Hear Again` to replay the challenge sound.
5. Earn stars for correct answers.

## Language Toggle

Use the top-right flag buttons:

- `🇸🇪 SV` (default)
- `🇬🇧 EN`

All labels, prompts, and animal text switch instantly.

## Accessibility Notes

- Large tap targets for young children
- High-contrast, simple visual hierarchy
- Predictable reward feedback on correct answers

## Credits

Audio clip credits and licenses are listed in:

- `AUDIO_CREDITS.md`

## License

Project code license: add your preferred license (e.g. MIT) in a `LICENSE` file.
Audio licensing varies by source; see `AUDIO_CREDITS.md`.
