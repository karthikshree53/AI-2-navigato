SETUP (Windows, VS Code terminal)
1. cd AI_Skill_Gap_Career_Navigator
2. pip install -r requirements.txt
3. Copy .env.example to a new file named .env  (keep the name exactly ".env")
   Put your real key:  GEMINI_API_KEY=AIza...      (get free: https://aistudio.google.com/apikey)
4. python app.py
5. Open http://127.0.0.1:5000/gemini-status?test=1   -> must say "GEMINI IS WORKING"
6. Register -> Skill Tests -> choose a skill.

If you still see old errors, stop the old server (CTRL+C) and run python app.py again.
If you changed the database model earlier and get a DB error, delete instance/app.db once.
