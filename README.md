# Minecraft sniffing

This script was used to sniff 10000+ Hypixel Skyblock
players during foraging update preparation.

## Usage

Install packages:
```
npm i
```

Run proxy:
```
npm start
```

Connect to minecraft server using Minecraft 1.8.9 at
`localhost:25566`

Upon connecting to server you will see this message
in console:
```
MSA code: XXXX
```

You will need to paste this in
[microsoft.com/link](https://microsoft.com/link) to
login into your minecraft account, that will be used
to login onto the server.

In case you want to use this technique with other
server or different version of the game, just change
ip address and version in `package.json`:
```
{
  ...
  "scripts": {
    "start": "node proxy.js <ip address> <mc version>"
  },
  ...
}
```
