# pythondev

This role installs packages / libraries associated with python development.

## role variables

|name|description|default|
|----|-----------|-------|
|`python.package`|python package|python2.7|
|`python.version`|python package version|2.7.3-5ubuntu4|
|`python.libraries.latest`|latest python packages to install|python-dev, python-pip, python-virtualenv|
|`python.libraries.versioned`|versioned python packages to install||
|`env.proxies`|dictionary of proxy related environment variables (http_proxy, https_proxy, ftp_proxy)||

See [defaults/main.yml](https://github.com/ryankanno/ansible-roles/blob/master/pythondev/defaults/main.yml)
