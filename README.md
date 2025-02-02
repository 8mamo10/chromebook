# chromebook

```
$ sudo apt-get update
Get:1 https://deb.debian.org/debian buster InRelease [122 kB]
Ign:2 https://storage.googleapis.com/cros-packages/94 buster InRelease
Get:3 https://deb.debian.org/debian-security buster/updates InRelease [65.4 kB]
Hit:4 https://storage.googleapis.com/cros-packages/94 buster Release
Reading package lists... Done
N: Repository 'https://deb.debian.org/debian buster InRelease' changed its 'Version' value from '10.9' to '10.11'
E: Repository 'https://deb.debian.org/debian buster InRelease' changed its 'Suite' value from 'stable' to 'oldstable'
N: This must be accepted explicitly before updates for this repository can be applied. See apt-secure(8) manpage for details.
E: Repository 'https://deb.debian.org/debian-security buster/updates InRelease' changed its 'Suite' value from 'stable' to 'oldstable'
N: This must be accepted explicitly before updates for this repository can be applied. See apt-secure(8) manpage for details.
yamamoto0810@penguin:~$  sudo apt --allow-releaseinfo-change update
Get:1 https://deb.debian.org/debian buster InRelease [122 kB]
Ign:2 https://storage.googleapis.com/cros-packages/94 buster InRelease
Get:3 https://deb.debian.org/debian-security buster/updates InRelease [65.4 kB]
Hit:4 https://storage.googleapis.com/cros-packages/94 buster Release
Get:5 https://deb.debian.org/debian buster/main arm64 Packages [7,735 kB]
Get:6 https://deb.debian.org/debian buster/main Translation-en [5,968 kB]
Get:8 https://deb.debian.org/debian-security buster/updates/main arm64 Packages [304 kB]
Get:9 https://deb.debian.org/debian-security buster/updates/main Translation-en [163 kB]
Fetched 14.2 MB in 9s (1,644 kB/s)
Reading package lists... Done
Building dependency tree
Reading state information... Done
47 packages can be upgraded. Run 'apt list --upgradable' to see them.
N: Repository 'https://deb.debian.org/debian buster InRelease' changed its 'Version' value from '10.9' to '10.11'
N: Repository 'https://deb.debian.org/debian buster InRelease' changed its 'Suite' value from 'stable' to 'oldstable'
N: Repository 'https://deb.debian.org/debian-security buster/updates InRelease' changed its 'Suite' value from 'stable' to 'oldstable'
yamamoto0810@penguin:~$ sudo apt-get update
Hit:1 https://deb.debian.org/debian buster InRelease
Hit:2 https://deb.debian.org/debian-security buster/updates InRelease
Ign:3 https://storage.googleapis.com/cros-packages/94 buster InRelease
Hit:4 https://storage.googleapis.com/cros-packages/94 buster Release
Reading package lists... Done
```

```
$ sudo apt-get install -y gnome-keyring
```

```
$ uname -a
Linux penguin 5.4.139-16311-g330b3df0010b #1 SMP PREEMPT Mon Nov 8 12:35:04 PST 2021 aarch64 GNU/Linux
$ dpkg --print-architecture
arm64
```

## vscode

- https://code.visualstudio.com/docs/?dv=linuxarm64_deb
