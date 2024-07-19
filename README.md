# Sing-Box-NGINX-WebSocket

### Trojan and VLESS WebSocket proxy with TLS termination on NGINX

> [!IMPORTANT]
> Recommended OS: Debian 12. Run as root on a newly installed system. It's recommended to update and reboot the system before running this script.

> [!NOTE]
> With routing rules for Russia.
 
### Includes:
1) Sing-Box server setup (Trojan and VLESS protocols)
2) NGINX reverse proxy and website setup
3) Basic security setup including unattended-upgrades
4) WARP setup
5) Cloudflare SSL certificates with auto renewal
6) Enable BBR
7) Client Sing-Box configs with routing rules for Russia
 
### Usage:

```
bash <(curl -Ls https://raw.githubusercontent.com/BLUEBL0B/Sing-Box-NGINX-WS/master/sb-nginx-server.sh)
```

If you also want to set up your *__own website__* on the server then upload the folder with its contents to *__/root__* directory before running the script, and the script will set it up for you.

### Client setup guidelines:
Android and iOS: [RU](https://github.com/BLUEBL0B/Sing-Box-NGINX-WS/blob/main/Client-Guidelines/Sing-Box-Android-iOS-ru.pdf), [EN](https://github.com/BLUEBL0B/Sing-Box-NGINX-WS/blob/main/Client-Guidelines/Sing-Box-Android-iOS-en.pdf)

Windows 10 and 11: [RU](https://github.com/BLUEBL0B/Sing-Box-NGINX-WS/blob/main/Client-Guidelines/Windows-10-11-ru.pdf), [EN](https://github.com/BLUEBL0B/Sing-Box-NGINX-WS/blob/main/Client-Guidelines/Windows-10-11-en.pdf)
