
# SoraOS temp repo

# Add repo to your system
add this to `/etc/pacman.conf`

```
[sora-tmp-repo]
SigLevel = Optional DatabaseOptional
Server = https://soraos.github.io/$repo/
```

# Update database
```
repo-add soraos-tmp-repo.db.tar.gz *.pkg.tar.zst
```
