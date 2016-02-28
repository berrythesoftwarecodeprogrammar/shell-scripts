# Shell scripts
bash things to help with server management

## Non-root scripts
### sslfp [🡇](https://raw.githubusercontent.com/berrythesoftwarecodeprogrammar/shell-scripts/master/sslfp)
Script to get the SSL/TLS fingerprints of remote servers. Got some help from [this blog post](https://mikaela.info/english/2015/02/24/znc160-ssl.html) and [this stackexchange post](https://unix.stackexchange.com/questions/126908/get-ssh-server-key-fingerprint)

Install: `mv -f sslfp /usr/bin/ && chmod +x /usr/bin/sslfp && chmod 755 /usr/bin/sslfp && chown root.root /usr/bin/sslfp`  
Usage: `sslfp <host|ip> <port> [-full]`  

## Root scripts
