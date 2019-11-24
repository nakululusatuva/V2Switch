# V2Switch
Manage multiple V2Ray configs and switch between them.

## Install
Download the script file to anywhere you want and give execute privilege.
```
wget https://github.com/Yirain/V2Switch/releases/download/v0.2/v2switch
chmod +x v2switch
```
[Optional] Move the script to `/usr/bin` for convenience of use.
```
mv v2switch /usr/bin/
```

## Usage
```
./v2switch [option] [parameters]
list                                List all profiles.
current                             Show current profile's name.
add         [file_path]             Add a profile from file "PROFILE.json".
apply       [profile]               Apply a profile and restart v2ray.
remove      [profile]               Remove a profile.
rename      [old] [new]             Rename a profile.
removeall                           Remove all profiles.
ping        [4/6] [profile]         Ping test with IPv4 or IPv6.
tracer      [4/6] [profile]         Traceroute with IPv4 or IPv6.
mtr         [4/6] [profile]         MTR test with IPv4 or IPv6.
setv2path   [dir_path]              Set the V2Ray config directory.
help                                Show this message.
```
