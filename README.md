## IRC Cheetsheet for my education IRC server

[![](https://img.shields.io/badge/chat-on%20gooseswell-brightgreen.svg)](https://gooseswell.mooo.com/) -> [gooseswell.mooo.com](https://gooseswell.mooo.com/)

To connect to my test server with standard IRC client:

```
gooseswell.mooo.com:6667      (unencrypted connection)
gooseswell.mooo.com:6697 +SSL (secure connection)
```

WebSocket connection details:

```
ws://gooseswell.mooo.com:8079  (unencrypted connection)
wss://gooseswell.mooo.com:8080 (SSL) (secure connection)
```

### To compile this website:

```
$ yarn global add pug-cli
$ chmod +x render.sh
$ serve html/
```
