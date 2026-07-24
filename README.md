# certsprint-reels-assets

Temporary public hosting for rendered videos from the CertSprint Instagram Reels bot.

Instagram's Graph API requires a publicly reachable `video_url` to publish a Reel - it does not accept direct file uploads. This repo exists solely so the bot can upload a rendered mp4 as a GitHub Release asset, hand that public URL to Instagram, and delete the release right after a successful publish.

No manual action needed here - it's managed entirely by the bot in [certsprint-reels-bot](https://github.com/AurelioAvila/certsprint-reels-bot).
