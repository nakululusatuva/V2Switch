# V2Switch
Manage multiple V2Ray configs and switch between them.

## Install
Download the script file to anywhere you want and give execute privilege.
```
wget https://github.com/Yirain/V2Switch/blob/master/v2switch
chmod +x v2switch
```
(Optional) Move the script to `/usr/bin` for convenience of use.
```
mv v2switch /usr/bin/
```

## Usage
```
./v2switch [option] [parameter]
list                           List all profiles.
current                        Show current profile name.
add        [file_path]         Add a JSON config, file name is the profile name.
apply      [profile_name]      Apply a profile and start v2ray.
remove     [profile_name]      Remove a profile.
removeall                      Remove all profiles.
setpath    [path]              Set the v2ray config path, default is /etc/v2ray/.
help                           Show this message.
```
