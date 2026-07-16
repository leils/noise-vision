# noise-vision / ghost-message frame viewer

Browse `ghost-message.mp4` one frame at a time in the browser.

## Run

```bash
cd noise-vision
python3 -m http.server 8765
```

Open **http://localhost:8765** in your browser.

> Must be served over HTTP — opening `index.html` directly as a `file://` URL breaks video seeking.

## Controls

| Key | Action |
|---|---|
| `→` | +1 frame |
| `←` | −1 frame |
| `↑` | +10 frames |
| `↓` | −10 frames |
| `Home` | first frame |
| `End` | last frame |
| drag scrubber | seek anywhere |
