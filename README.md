# InspiroCord
A Python script to generate quotes using [InspiroBot](https://inspirobot.me)'s API and send them to a Discord webhook.

This script will generate and send a new quote every 5 minutes as long as the script is running.

## How to setup

- Clone the repository using `git`:
```
$ git clone https://github.com/xDrixxyz/InspiroCord
```

- Copy `config.example.json` to `config.json`

- Edit the values in `config.json` by entering your webhook URL and optionally changing the timeout (read more below).

- Run `inspirocord.py` (If you're on Linux, `chmod +x ./inspirocord.py` first!)

- Enjoy!

### What is the `timeout` setting in the config?
`timeout` lets you set the amount of time, in **SECONDS**, that should pass before generating and sending another quote to the webhook.

It's recommended to leave the default value of 300, which is 5 minutes.
