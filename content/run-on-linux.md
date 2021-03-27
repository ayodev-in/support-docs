+++
title = 'How to run playit.gg on Linux'
tags = ["linux"]
+++

First things first, you'll need to download the latest version of the playit.gg agent from [playit.gg/download](https://playit.gg/download).

When you try to run the program, you might get errors like

![linux bad run ubuntu]({{< static "post-img/linux-run-bad-ubuntu.png" >}})
![linux bad run cli]({{< static "post-img/linux-run-bad-cli.png" >}})

## The Fix

You'll need to make the program runnable on linux. You can do this by running `chmod +x`.

```bash
cd ~/Downloads # cd into the folder where the playit program is located
chmod +x playit-linux_64-{{< latest-version >}}
./playit-linux_64-{{< latest-version >}}
```

To download and run the playit program you can use

```bash
wget https://playit.gg/downloads/playit-linux_64-{{< latest-version >}}
chmod +x playit-linux_64-{{< latest-version >}}
./playit-linux_64-{{< latest-version >}}
```

If you're interested in running playit 24/7 on a linux computer/server, see {{< link "host-247-with-playit" >}}
