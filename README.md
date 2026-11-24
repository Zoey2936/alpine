```sh
wget -O /etc/apk/keys/zoey2936.rsa.pub https://zoey2936.github.io/alpine/zoey2936.rsa.pub
echo https://zoey2936.github.io/alpine | tee -a /etc/apk/repositories
```

with apk-tools 3 (Alpine 3.23 and later) the v3 index can be used instead:

```sh
wget -O /etc/apk/keys/zoey2936.rsa.pub https://zoey2936.github.io/alpine/zoey2936.rsa.pub
echo v3 https://zoey2936.github.io/alpine | tee -a /etc/apk/repositories
```
