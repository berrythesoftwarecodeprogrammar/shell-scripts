# Shell scripts
bash things to help with server management

## Non-root scripts
### sslfp
Script to get the ssl/tls fingerprints of remote servers  
Install: `mv -f sslfp /usr/bin/ && chmod +x /usr/bin/sslfp && chmod 755 /usr/bin/sslfp && chown root.root /usr/bin/sslfp`  
Usage: `sslfp <host|ip> <port> [-full]`  
Borrowed code from [this blog post](https://mikaela.info/english/2015/02/24/znc160-ssl.html) and [this stackexchange post](https://unix.stackexchange.com/questions/126908/get-ssh-server-key-fingerprint)

## Root scripts
