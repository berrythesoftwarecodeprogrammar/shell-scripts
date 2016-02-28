# shell scripts
bash things to help with server management

## non-root scripts
### sslfp
script to get the ssl/tls fingerprints of remote servers

`mv -f sslfp /usr/bin/ && chmod +x /usr/bin/sslfp && chmod 755 /usr/bin/sslfp && chown root.root /usr/bin/sslfp`

Usage: sslfp <host|ip> <port> [-full]

## root scripts
