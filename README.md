# voice-agent
readme = f"""
# Ultra-Lite Voice Agent (Notebook)

This notebook records audio from mic, transcribes it, gets an AI reply (**Gemini** or mock), speaks it back,
and extracts simple form fields (name/email) from the spoken text.

## How to Run
1. Run the install cell.
2. Record audio (or upload file).
3. Transcribe (SpeechRecognition).
4. Get AI reply (set `USE_GEMINI=True` and provide `GEMINI_API_KEY` to use Gemini; otherwise mock).
5. Text-to-speech playback.
6. Form extraction and latency printout.

## Get a Gemini API Key
1. Open: https://aistudio.google.com/app/apikey
2. Sign in and click **Create API key → Create API key in new project**.
3. Copy the key (looks like `AIza...`).

### Configure the key (choose one)

**A) Environment variable (recommended)**
- Windows PowerShell:
