# ClassWatch
Laptop-only classroom noise-monitoring demo. Arduino is optional.

## Run on Windows
1. Open this folder in VS Code.
2. In Terminal run: `python -m pip install -r requirements.txt`
3. Run: `python app.py`
4. Open http://127.0.0.1:5000
5. Press Start monitoring and allow microphone access.

Features: live relative sound level, green/yellow/red status, red-alert counter,
recent alerts, adjustable threshold, optional camera preview and snapshots.
Sound values are relative, not calibrated dB. Camera is off by default.
Use camera capture only with the knowledge and permission of people present.
Audio is processed in the browser; this demo does not upload recordings.
