# Privacy Policy

**Effective date:** April 24, 2026

Breakfast Ball is an iOS app that lets golfers track scores during group trips. This policy explains what we collect and why.

## What we collect

- **Profile information you enter:** name, optional nickname, optional handicap index, optional GHIN number, optional profile photo.
- **Trip activity:** the trips you join, the rounds you play, the scores you enter, and chat messages you post in the group chat.
- **Authentication:** an anonymous user identifier issued by Firebase Authentication. We do not collect email addresses, passwords, or phone numbers from you.
- **Coarse location (only when adding a trip):** used once to find nearby golf courses. We do not store your location.
- **Device data:** standard crash and performance data needed to keep the app running.

We do **not** collect contact lists, call logs, browsing history, health data, financial data, or device identifiers used for advertising. We do **not** track you across other apps or websites.

## How we use it

- To run the trip you joined: synchronizing scores, surfacing a leaderboard, sending birdie / shame chat events.
- To generate AI round and trip recaps via Anthropic's Claude API. The scores, names, and round metadata for the relevant trip are sent to Anthropic for the duration of generating the recap. Anthropic does not use this data to train models. See Anthropic's privacy policy at https://anthropic.com/privacy.
- To search for nearby courses via Google Places. Your search query and coarse location are sent to Google for the duration of that request only. See Google's privacy policy at https://policies.google.com/privacy.
- To respond to community guidelines reports.

## Storage and retention

- Active trip data is stored in Google Firestore (Firebase) under your anonymous user ID.
- Profile preferences are stored locally on your device in iOS UserDefaults.
- You can permanently delete your account in **Settings → Delete Account**. This removes your profile, scores, chat messages, and any trips where you were the only player. Trips with other players remain intact (you are removed from the roster). Reports submitted prior to deletion may be retained for moderation review.

## Children

Breakfast Ball is intended for users 13 years of age or older. We do not knowingly collect personal information from children under 13.

## Contact

For privacy questions or to request deletion outside the app, email **privacy@breakfastball.app**.
