# {{ page.app }}: Privacy Policy

_Last updated: {{ site.last_updated }}_

This explains what **{{ page.app }}**, run by {{ site.operator }} ("we"), stores and why. The short version: we keep only what the commands need, we never sell it, and you can ask us to delete it.

## What we store
- **Discord IDs:** the server ID, channel IDs, and the user IDs of people who use commands. These are numbers Discord assigns; we don't store email addresses or passwords.
- **Server settings:** the options admins choose with the setup commands.
{% for item in page.stores %}- {{ item }}
{% endfor %}- **Usage counts:** how many commands a server uses each day, so limits and abuse protection work.
- **Premium status:** whether a server or user has Premium, as reported by Discord. Discord handles payments; we never see card details.
- **Error logs:** when a command fails, we log the command name, server ID and error, kept up to 30 days, to fix bugs.

## What we don't do
- We don't read messages in your channels. The app only sees what you type into its own slash commands.
- We don't sell or rent your data, or use it for advertising.
{% if page.ai %}
## AI processing
{{ page.ai }}
{% endif %}
## Who else handles it
- **Discord** delivers commands and handles Premium payments ([Discord Privacy Policy](https://discord.com/privacy)).
- Our server host stores the app's database.
{% for p in page.processors %}- {{ p }}
{% endfor %}
## How long we keep it
- While the app is in your server, we keep the data so its features work.
- When the app is removed from a server, we delete that server's data within 30 days.
- Backups roll over and are gone within 30 days after that.

## Your choices
- Server admins can remove the app at any time, which starts the deletion above.
- Anyone can ask us to see or delete the data tied to their Discord user ID. Email {{ site.contact_email }} with your user ID, and we'll reply within 30 days.

## Children
Discord requires users to be at least 13 (or older where local law says so). The app isn't meant for anyone younger.

## Changes
We'll update the date above when this policy changes. Big changes will also be posted in the support server.

## Contact
{{ site.contact_email }}. See also the [Terms of Service](terms.html).
