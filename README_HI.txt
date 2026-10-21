QuizBattleWar — Firebase Online Update

Included:
- index.html: existing QuizBattleWar app file with Google sign-in, online 1-vs-1 matchmaking code, optional Bot fallback after waiting, and Firebase public-profile leaderboard code.
- database.rules.json: Firebase Realtime Database rules matching the app's paths.

To use:
1. Upload index.html to your website/hosting in place of the currently hosted app file.
2. In Firebase Console > Realtime Database > Rules, publish database.rules.json contents.
3. Test with two different Google accounts in two separate browsers/devices.

Important:
- Publishing database rules alone does not update the website's HTML.
- Live matchmaking has not been verified against two real accounts in this environment.
- These client-side score/wallet fields are not cheat-proof; use trusted server-side validation before any real-money rewards.
