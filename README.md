# github actionを使ってgithubのdockerの中でubuntu linuxのコンテナイメージを使ってqemuをarm64(aarch64)で動かすサンプルです。

```
Run uname -a
Linux fv-az120-315 5.4.0-1031-azure #32~18.04.1-Ubuntu SMP Tue Oct 6 10:03:22 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux

Run sudo chroot ./ubuntu-20.04-arm64 /bin/uname -a
Linux fv-az120-315 5.4.0-1031-azure #32~18.04.1-Ubuntu SMP Tue Oct 6 10:03:22 UTC 2020 aarch64 aarch64 aarch64 GNU/Linux
```
