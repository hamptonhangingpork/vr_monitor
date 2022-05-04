# Prerequisites

Script requires the following applications/services
- *Python3 if run on local machine*
- *Bot hosting server (suggestion: https://replit.com/ - https://www.youtube.com/watch?v=SPTfmiYiuok)*
- *Ping server (suggestion: http://freshping.io/ or https://uptimerobot.com/)*

It will also might require the following python libraries
- *Flask*
- *Discord Webhook*

You can install them by invoking the following in commandline
```
pip install Flask
pip install pip install discord-webhook
```

# Getting Started

Before running the script, please make sure the following variables are properly set up -

- webhook_url
  * Create a webhook for your desired channel - Edit Channel -> Integration -> Webhooks -> New Webhook

- kw_list
  * Add keywords to monitor here. Use quotes and seperate keywords by ',' - ex. ['kanye west', 'boldy james']

- myid
  * Get your Discord user id - Turn on Discord dev mode (https://www.howtogeek.com/714348/how-to-enable-or-disable-developer-mode-on-discord/) -> Right-click on your profile in the member pane -> Copy ID

- subreddit
  * Currently set to 'vinylreleases'. You can easily change this to any subreddit that you want to monitor


# Running the script

```
python main.py
```
