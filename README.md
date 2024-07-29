# 适用于 Centos 的 Chrome 历史版本

    wget https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm
    yum localinstall google-chrome-stable_current_x86_64.rpm

在 Centos 安装 Chrome 时，提示 Error: Invalid version flag: or

    Loaded plugins: fastestmirror, langpacks
    Repository epel is listed more than once in the configuration
    Examining google-chrome-stable_current_x86_64.rpm: google-chrome-stable-127.0.6533.72-1.x86_64
    Marking google-chrome-stable_current_x86_64.rpm to be installed
    Resolving Dependencies
    --> Running transaction check
    ---> Package google-chrome-stable.x86_64 0:127.0.6533.72-1 will be installed
    Error: Invalid version flag: or

可能版本不兼容，这个是 127.0.6533.72 版，但 Google 好像不提供历史版本下载


https://www.slimjet.com/chrome/google-chrome-old-version.php  这里版本又太老了

就从以前安装过 Chrome 的服务器上，找了 120.0.6099.216 、123.0.6312.58 两个版本，放 github 存档






