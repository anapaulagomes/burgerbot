# BurgerBot

I was frustrated with the lack of available slots in Burgeramt, so I've created this bot for myself,
to catch one that available.
It's pretty straightforward, once per 30 seconds it parses page with all appointments in all Berlin
Burgeramts and if there is available slot for current and next month - it notifies in telegram with
the link to registration.

## Configuration

Create a bot on Telegram and set the env var `TELEGRAM_API_KEY` with its key.

## Bot instructions

```
/start - start the bot
/stop - stop the bot
/add_service <service_id> - add service to your list
/remove_service <service_id> - remove service from your list
/my_services - view services on your list
/services - list of available services
```

