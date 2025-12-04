# Debian Live Build

```
git clone https://salsa.debian.org/live-team/live-build.git debian-live-build
cd debian-live-build
sudo make install
sudo lb --version
sudo lb clean --purge
sudo lb config
sudo lb build
```

We will have `live-image-amd64.hybrid.iso` ready to boot.

# References

- https://www.debian.org/devel/debian-live/
- https://live-team.pages.debian.net/live-manual/html/live-manual/index.en.html
- From BlankOn wiki: https://github.com/BlankOn/wiki/blob/master/TimPengembang/Pemaket/LiveBuild.md
