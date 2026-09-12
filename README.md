Tactical AI Coach
An intelligent cross-platform tactical coaching tool for Valorant and Counter-Strike 2. It analyzes match timelines, exact round death timestamps, map control failures, and choke points using automated API telemetry and Gemini AI to deliver actionable tactical improvement strategies.

Features
Multi-Game Support: Analyzes match data for both Valorant (via Henrik's API) and CS2 (via Steam/Community APIs).

Death Timing Analysis: Tracks exact millisecond timestamps and map coordinates where players get caught or isolated.

Choke Point Diagnostics: Identifies structural site-execution breakdowns (e.g., how mid-control failures funnel teams into dead ends).

Actionable Counter-Strategies: Generates precise, round-by-round adjustments to fix mid-round pacing and utility usage.

Collaborative Architecture: Clean separation between the Streamlit UI (app.py) and backend logic (backend.py).

Tech Stack
Frontend: Streamlit

Backend Logic & AI: Python, Google Gemini API

Data Sources: Henrik's Unofficial Valorant API, Steam Web API / CS2 Community Telemetry
