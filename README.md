# Doichi GPT

The ChatGPT (OpenAI API) edition of Doichi: Lesefreund, Satzdoktor, Sag's auf Deutsch!, Kaffeeklatsch.
It keeps its own settings, separate from the Gemini "Doichi" app, even on the same phone.

## Put it online (GitHub Pages)
1. On GitHub: New repository → name `doichi-gpt` → Public → Create.
2. "uploading an existing file" → drag in ALL files from this folder (not the folder itself) → Commit changes.
3. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
4. After ~1 minute: https://YOUR-USERNAME.github.io/doichi-gpt/

## Install on iPhone
Open the link in Safari → Share → "Add to Home Screen" → Add.

## OpenAI key
1. https://platform.openai.com/api-keys → Create new secret key.
2. Add credit under Billing (a ChatGPT Plus subscription does NOT include API access).
3. In Doichi GPT → Einstellungen → paste the key → "Verbindung testen".
Default models: `gpt-6.1-sol` (main) and `gpt-6-luna` (fast, very cheap). For the lowest cost, use `gpt-6-luna` in both fields.

## Voices
Einstellungen → Stimme: natural OpenAI voices (Marin, Cedar, Coral, Nova …) via `gpt-4o-mini-tts`, or the free device voice.
Each sentence is generated once and then stored on the phone, so replays cost nothing.
