![Repo Build Status](https://img.shields.io/github/actions/workflow/status/zaggash/archlinux-aur/run-build-repo.yaml?label=REPO%20BUILD&logo=archlinux&logoColor=white&style=for-the-badge)
![Renovate](https://img.shields.io/github/actions/workflow/status/zaggash/archlinux-aur/run-renovate.yaml?label=renovate&logo=RenovateBot&logoColor=white&style=for-the-badge)  
![GitHub release (release name instead of tag name)](https://img.shields.io/github/v/release/banhammerykt/archlinux-aur?display_name=release&include_prereleases&label=Latest%20Repo%20Build&logo=archlinux&style=for-the-badge)

## My Archlinux repo

This is an unofficial repository for Arch Linux.  
Originaly intended to fit my needs and build custom or unavailable packages.

### How to use it

- Edit `/etc/pacman.conf` with:

```
[archlinux-aur]
Server = https://github.com/banhammerykt/$repo/releases/download/$arch
SigLevel = Never
```

- Then update the DB:

```
pacman -Syy
```
