# HOURLY-DIGEST-BOT
A little n8n automation I built that emails me every hour with the weather and top news headlines.

I got tired of checking a weather app, then a news app, then somehow ending up doomscrolling for 20 minutes. So now it just comes to me — one quick email, no apps to open.

What it does ????
- Runs every hour (Schedule Trigger)
- Grabs current weather from Open-Meteo
- Pulls a few top headlines from a news API
- Uses an AI node to format it into a short, readable summary
- Sends it straight to my inbox

Built with :
- n8n
- Open-Meteo API (weather)
- Hacker News (Algolia API) - for: top tech/startup stories
- Email/SMTP (or Gmail node)
