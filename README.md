# heroku-cmake-buildpack-bin

A pre-compiled version of https://github.com/brave/heroku-cmake-buildpack

login to the heroku server
```bash
heroku run sh -a brave-cmake-buildpack-builder
```

on the heroku server
```bash
./package.sh
```

on the original computer
```bash
wormhole receive KEY-FROM-PACKAGE-SH
```
