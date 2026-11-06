# TRADEFORGE AI - Python Multi-Agent Algorithmic Trading Platform (v4.0)

## Overview
TRADEFORGE AI is an autonomous, multi-agent trading platform featuring 15 dedicated workspaces, full speech control, real-time marketplace charting, and an asynchronous Python FastAPI orchestration backend.

## File Structure
- `index.html`: Web interface with speech pause button, live charts, and 15 agent ROI tracking.
- `main.py`: Modular Python async backend engine handling all 15 agents, task counters, and WebSocket telemetry.
- `requirements.txt`: Python package requirements.

## How to Run locally:
1. Install Python packages:
   ```bash
   pip install -r requirements.txt
   ```
2. Start the FastAPI Python Engine:
   ```bash
   uvicorn main:app --reload --port 8000
   ```
3. Open `index.html` in your web browser.
