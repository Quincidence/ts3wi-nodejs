# ts3wi-nodejs
Administrate TeamSpeak 3 servers via a web page.
NodeJS server hosts a web interface running [Socket.IO](http://socket.io/) JavaScript which polls the NodeJS server to query the TeamSpeak 3 server, then relays the data back to the web interface.
This exact Git is hosted on a free Heroku Dynamo (very small host) which is why initial connection can take some time. (Pings after initial connection will show actual ping time.) It's essentially some form of proxy.
No security risk due to the intended programs use is therefore apparent, due to public 'server.js' file.

Visit https://quincidence.github.io/ts3wi-nodejs/ for the front end :)

# Not in development. Happy for contributions.


## Todo List:
  1. A lot.
  2. Editing channels and clients.
  3. Check for loopholes.
  4. more...

## History
TS3WI-NodeJS was in development for about a month (January 2017) as a side project, I have no interest in it right now.

Inspired by Psychokiller's PHP version. (files on [random GitHub](https://github.com/maxlin1990/ts3web) host, visit the [support forum](http://interface.ts-rent.de/smf/index.php?page=Board&boardID=2) for Psychokiller's official releases)
