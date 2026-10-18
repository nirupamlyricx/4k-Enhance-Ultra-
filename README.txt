Backend starter (Node.js 20+)
1. Copy .env.example to .env and set a unique JWT_SECRET (>=32 characters), FRONTEND_ORIGIN, and DB_PATH.
2. Install dependencies: npm install
3. Export the environment variables from .env using your hosting platform's secret settings, then run: npm start
4. Set the app's Cloud API Base to the backend base URL (for example https://api.example.com). The app calls /register, /login and /sync.
5. Deploy behind HTTPS. Keep database files private and backed up. Add email verification, password reset, monitoring and a privacy policy before public production use.
Do not commit real secrets or expose the database file publicly.
