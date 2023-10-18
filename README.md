# rsync in Git bash
In this repository, you learn to install the rsync package for Windows users.

1. Install Git: https://git-scm.com/downloads
2. From [rsync-3.2.3-2-x86_64.zip](rsync-3.2.3-2-x86_64.zip) put usr/bin/rsync.exe into C:\Program Files\Git\usr\bin .
3. From [libzstd-1.5.5-1-x86_64.pkg.tar](libzstd-1.5.5-1-x86_64.pkg.tar) put usr/bin/msys-zstd-1.dll into C:\Program Files\Git\usr\bin .
4. From [libxxhash-0.8.2-1-x86_64.pkg.tar](libxxhash-0.8.2-1-x86_64.pkg.tar) put usr/bin/msys-xxhash-0.dll into C:\Program Files\Git\usr\bin .
5. Restart Git bash.

To verify try:
```
rsync --version
```
