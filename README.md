# Screenshot

![screenshot](https://github.com/nomura-lab/dps/blob/images/screenshot.png)

# How to install

```
wget -O - https://github.com/nomura-lab/dps/releases/download/v1.0.0/dps_1.0.0_linux_amd64.tar.gz | tar zxvf -
```

# How to use

```
./dps
```

When you get blow error,

```
panic: Error response from daemon: client version <x.xx> is too new. Maximum supported API version is <y.yy>
```

you have to use `--apiversion` flag to avoid it.

```
./dps --apiversion <y.yy>
```


