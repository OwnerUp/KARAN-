KARAN REPORTER - Tracking v3

Upload index.html and dp.jpg together, replacing the old files.
Test on the PUBLIC hosted page (not file://). Open Meta Events Manager > Test Events.
Clear site cache/CDN and use an incognito browser with ad blocker disabled.
Click Subscribe Now. Expect PageView plus TelegramJoinClick (custom) and Subscribe (intent-only) if Meta Pixel is allowed.
These click events do not verify joining the Telegram channel.
If only PageView shows, inspect the live page source to confirm the new code was deployed and check browser DevTools Network for facebook.com/tr requests.
