# Qui a dit ça ?
_Qui a dit ça ? Le fameux jeu de la CLIC_

### Requirements

Install the right [Telegram API wrapper](https://github.com/python-telegram-bot/python-telegram-bot) for Python. Namely

```
$ pip install python-telegram-bot
```

See the Telegram API documentation to obtain your bot token, to be stored in a ```.keys``` file under ```token=YOUR_TOKEN```. Then simply launch the bot
```
$ python bot.py
```
You can edit the list of people _qui l'ont peut-être dit_ via a direct edit of the JSON file ```options.json```. The key should be a unique and simple identifier of a possibily fancy value. Typically, you want to add an entry of the form ```"francois": "François"``` or ```4: "François"```.

Enjoy!
