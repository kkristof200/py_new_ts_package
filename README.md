# py_new_ts_package

create new ts package

# Install (tested on mac)

```bash
# via wget

wget https://github.com/kkristof200/py_new_ts_package/blob/master/new_ts_package -O /usr/local/bin/new_ts_package && chmod u+x /usr/local/bin/new_ts_package

wget https://github.com/kkristof200/py_new_ts_package/blob/master/.ntpconfig.json -O ~/.ntpconfig.json

# or via curl

curl https://github.com/kkristof200/py_new_ts_package/blob/master/new_ts_package > /usr/local/bin/new_ts_package && chmod u+x /usr/local/bin/new_ts_package

curl https://github.com/kkristof200/py_new_ts_package/blob/master/.ntpconfig.json > ~/.ntpconfig.json


# OPTIONALLY CREATE SYMLINK

ln -s "/usr/local/bin/new_ts_package" "/usr/local/bin/ntp"

```
