Welcome to BOT-CAFETERIA-EPCC!
===================
This project is a Telegram bot responsible for providing the daily menu of the cafeteria of the Polytechnic School of Cáceres.

-------

Dependencies
-------
These are the libraries needed to run the project.

List of dependencies
: [Tweetpy][1]
: [TelegramBotAPI][2]


Configuring the bot
-----
First of all we should go to the folder **koolfood/etc**.
Once there we must fill in the tokens:
Key    | Value 
-------- | -------
Telegram Api-token    | Token from your telegram bot (from botFather)
Twitter Consumer-Key | Key from Twitter
Twitter Consumer-Secret| Consumer from Twitter
Twitter Accesss-Token| Access token from Twitter
Twitter Access-Secret| Access secret from Twitter

Once we have this configured, we can run our bot.

-----------------
Executing the bot
------
To execute our bot we execute the script in the following way.

```
python koolfood/main.py koolfood/etc/config.json
```

In this way we will execute the bot with the configuration of the APIs used.

Usage 
----
Steps to use the bot.
: Find the bot *@Felipes_Cuisine_Bot* in this case.
: Use the */start* command.
: Profit !

-----

Contact
----
Feel free to contact with any doubt.
Authors
: [JuanPTM][4]
: [Mhaut][3]

  [1]: http://www.tweepy.org/
  [2]: https://github.com/eternnoir/pyTelegramBotAPI
  [3]: https://github.com/mhaut
  [4]: https://github.com/juanptm 