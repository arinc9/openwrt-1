Add tracebox feed to the bottom of `feeds.conf.default`:
```
src-git tracebox https://github.com/tracebox/tracebox-openwrt.git
```

Refresh feeds and install tracebox feed
```
./scripts/feeds update -a && ./scripts/feeds install -a
```
