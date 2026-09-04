# imagine-packs

Prywatne archiwum paczek z Perfect Generator.

Każda ukończona generacja ląduje tutaj jako **jeden plik ZIP** plus krótki manifest JSON.

```
packs/
  YYYYMMDD_HHMMSS__Fanpage__post.zip
  YYYYMMDD_HHMMSS__Fanpage__post.json
```

Wewnątrz ZIP-a:

- `001.jpg`, `002.jpg`, … — JPEG 2:3 (post) albo 9:16 (rolka)
- `prompts/001.txt` — prompt użyty do Grok Imagine
- `manifest.csv` — numer, plik, kartka, caption, status
- `sign_texts.txt` / `captions.txt`
- `run_state.json` — pełny plan paczki

Nie commituj kluczy API. Repo jest prywatne.
