NexGen BPO - Investor Pilot

Deploy on Render:
- Build: pip install -r requirements.txt
- Start: gunicorn -k uvicorn.workers.UvicornWorker main:app

Set ELEVENLABS_API_KEY in Render environment variables.
