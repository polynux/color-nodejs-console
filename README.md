# color-nodejs-console
Color code for nodejs console log

Reset: "\x1b[0m" <br/>
Bright: "\x1b[1m"<br/>
Dim: "\x1b[2m"<br/>
Underscore: "\x1b[4m"<br/>
Blink: "\x1b[5m"<br/>
Reverse: "\x1b[7m"<br/>
Hidden: "\x1b[8m"

FgBlack: "\x1b[30m"<br/>
FgRed: "\x1b[31m"<br/>
FgGreen: "\x1b[32m"<br/>
FgYellow: "\x1b[33m"<br/>
FgBlue: "\x1b[34m"<br/>
FgMagenta: "\x1b[35m"<br/>
FgCyan: "\x1b[36m"<br/>
FgWhite: "\x1b[37m"

BgBlack: "\x1b[40m"<br/>
BgRed: "\x1b[41m"<br/>
BgGreen: "\x1b[42m"<br/>
BgYellow: "\x1b[43m"<br/>
BgBlue: "\x1b[44m"<br/>
BgMagenta: "\x1b[45m"<br/>
BgCyan: "\x1b[46m"<br/>
BgWhite: "\x1b[47m"

![color-code](https://i.stack.imgur.com/ylEBX.gif)

Exemple: console.log("\x1b[31m%s\x1b[0m", "Some red text")
