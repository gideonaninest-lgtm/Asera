# ASERA — installable build

Voice and AI both run through small server functions, so your API keys never reach the phone.

## Deploy (Vercel)
1. Put this folder in a GitHub repo (use git push or GitHub Desktop, not the browser uploader).
2. Import the repo in Vercel. No build settings needed.
3. Project → Settings → Environment Variables:
   - `ANTHROPIC_API_KEY` — Claude replies
   - `ELEVENLABS_API_KEY` — ElevenLabs voice
   - `ASERA_ACCESS_CODE` — any passphrase; strongly recommended so nobody else spends your credits
   - optional: `ELEVENLABS_VOICE_ID` (default NOpBlnGInO9m6vDvFkFC), `ASERA_MODEL_FAST`, `ASERA_MODEL_DEEP`
4. Redeploy after adding the variables.

## Install
- Android: open the site in Chrome → ⋮ menu → Install app.
- Windows: open it in Edge or Chrome → install icon in the address bar.
