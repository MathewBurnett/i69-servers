# i69-servers
nice

```
 Install Nix in single-user mode
# https://nixos.org/download.html
$ sh <(curl -L https://nixos.org/nix/install) --no-daemon

# Enable the new CLI and flakes
$ mkdir -p ~/.config/nix
$ echo 'experimental-features = nix-command flakes' >> ~/.config/nix/nix.conf

# Fetch and run the server
$ nix run github:ldesgoui/i69-servers#run
do you want to allow configuration setting 'extra-substituters' to be set to 'https://i69-servers.cachix.org' (y/N)? y
do you want to permanently mark this value as trusted (y/N)? y
do you want to allow configuration setting 'extra-trusted-public-keys' to be set to 'i69-servers.cachix.org-1:mH3TBiferuVUu5ufo3BFlY+aCyjNGK2oPa3XXHYDnGk=' (y/N)? y
do you want to permanently mark this value as trusted (y/N)? y
[1/10/35 built, 40 copied (136.0 MiB), 25.4 MiB DL] ...
---
--- State dir:     /home/ubuntu/tf2ds
--- Password:      XNQKCYSTKBYWJBFN
--- Rcon password: QFLI2O6B3RBLAIHS
---
Using Breakpad minidump system. Version: 7341704 AppID: 232250
Setting breakpad minidump AppID = 232250
...
```
