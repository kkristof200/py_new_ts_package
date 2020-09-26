# py_new_ts_package

create new ts package

# Setup
1. Install (tested on mac)
```bash
# via wget
wget https://github.com/kkristof200/py_new_ts_package/blob/master/new_ts_package -O /usr/local/bin/new_ts_package && chmod u+x /usr/local/bin/new_ts_package
wget https://github.com/kkristof200/py_new_ts_package/blob/master/.ntpconfig.json -O ~/.ntpconfig.json

# or via curl
curl https://github.com/kkristof200/py_new_ts_package/blob/master/new_ts_package > /usr/local/bin/new_ts_package && chmod u+x /usr/local/bin/new_ts_package
curl https://github.com/kkristof200/py_new_ts_package/blob/master/.ntpconfig.json > ~/.ntpconfig.json

# optionally create symlink
ln -s "/usr/local/bin/new_ts_package" "/usr/local/bin/ntp"
```
2. Update '.ntpconfig.json'
```json
{
    "version": "TO USE IN package.json",
    "author": "TO USE IN package.json",
    "package": "TO ADD TO 'package.json'",
    "tsconfig": "TO ADD TO 'tsconfig.json'",
    ".npmgitignore": "TO ADD IN '.npmgitignore'",
    ".gitignore": "TO ADD IN '.gitignore'",
    "needed_modules": "MODULES TO INSTALL AFTER RUNNING SCRIPT"
}
```

# Usage
```bash
cd to_desired_new_folder_path
new_ts_package # or ntp if created symlink
```
