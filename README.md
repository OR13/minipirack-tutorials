### Setting Up MiniPiRack

See https://www.minipirack.com/faq/

You may need to install [nmap](https://nmap.org/)

After plugging in your rack... wait for a while then nmap to find the IPs!

```
nmap 192.168.1.0/24
```

They will look like:

```
Nmap scan report for p3-r1 (192.168.1.228)
Host is up (0.0062s latency).
Not shown: 999 closed ports
PORT   STATE SERVICE
22/tcp open  ssh
```

Now ssh to it!

```
ssh pirate@192.168.1.228
```

Default password is `hypriot`... probably want to change that now.