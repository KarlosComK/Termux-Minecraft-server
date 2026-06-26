# How to make you termux server public to your friends play with you!

Since mobile devices dont have public ip, you have to use a **proxy/vpn** or a *tunnel* to friends play with you in different internet.

## Option 1: Playit.gg for linux (Highly recommend)
**Playit.gg** is the best option because it make a tunnel with the ip of your device, and "make it public" to anyone use or enter the server

## Step 1
open a dedicated playit gg session on termux, and execute this command to install the TUR repo (the termux user repository that have the playit gg package)
```bash
pkg install tur-repo
```

## Step 2
when the TUR repo download finish, install the playit gg package executing the command
```bash
pkg install playit
```

## Step 3
now, to setup playit gg, execute the commands
```bash
playitd &
```
and
```bash
playit-cli
```

# Congratulations!
when you finish the playitgg setup, you can execute the Minecraft server on a session, and playit gg on other session, and share the ip that playit gg generate!