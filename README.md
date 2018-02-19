# Live Trivia Bot...

CURRENTLY ONLY SUPPORTS HQ. THE Q SUPPORT WILL BE COMING LATER TODAY.


PLEASE NOTE: This bot was constructed from HQ-Trivia-Assistant by Mike Almond. Designed and re-created to be made for other trivia games, and more accurate.

Made by Nolan Platt and being created for almost all live trivia game shows via web socket.

How does it works? It gets into into the live trivia game shows web-socket stream and automatically searches Google and Yahoo! for the correct answer using different searches. 


Installing...

Clone/download zip of project file via GitHub
 cd LiveTriviaBot
 composer install
 cp .env.dist .env
```

**SET GAME IN `game.env.dist ` **

After you've created the .env file, fill in your Live Trivia Game(of your choice) user ID and bearer token. You can find your ID and token by sniffing the web traffic from your phone using a tool such as [Charles Proxy](https://www.charlesproxy.com/).

Fill in token and ID in the .env file for specific game show.

Installation assumes that you have installed [Composer](https://getcomposer.org/doc/00-intro.md#globally) already.

Running:
 php run.php
```


## Contributing

Feel free to contribute to this project.

## Authors/Credits

- [Mike Almond][link-author]
- [Nolan Platt][https://github.com/nolanplatt]
