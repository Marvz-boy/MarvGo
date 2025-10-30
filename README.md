# MarvGo
Search Engine
 MarvGo (local dev)
 
1. Install Node.js (v18+ recommended).
2. Copy `.env.example` → `.env` and add your `GOOGLE_API_KEY` and
`GOOGLE_CSE_ID`.
3. Run `npm install` to install dependencies.
4. Start the server: `npm run start` (or `npm run dev` while developing).
5. Open `http://localhost:3000` in your browser.
Notes:

- Keep `.env` secret. Do not commit it.
- If you want to host this publicly, move the proxy server to a secure server so
the key isn't exposed in a public repo
