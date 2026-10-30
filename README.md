# MusicPlayerBacground

A music player that keeps playing when the app is backgrounded.

## Highlights

- Background audio playback via `assets_audio_player`.
- Provider drives play, pause and track state across the UI.
- Track metadata separated into `model`, with reusable `widgets`.

## Tech Stack

| Concern | Choice |
|---|---|
| UI | Flutter, Material |
| State management | `provider` |
| Audio | `assets_audio_player` |

## Project Structure

```
lib/
- `model`
- `provider`
- `screen`
- `widgets`
```

## Getting Started

### Prerequisites

- Flutter `>= 3.16` (Dart `>= 3.2`)

### Run

```bash
git clone https://github.com/developer-rahim/MusicPlayerBacground.git
cd MusicPlayerBacground
flutter pub get
flutter run
```

### Test

```bash
flutter test
flutter analyze
```

## Notes

Background playback continues while the app is minimised — handle audio focus for production use.

## License

Released under the MIT License.
