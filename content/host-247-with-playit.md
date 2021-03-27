+++
title = 'How to run playit 24/7 on Linux'
tags = ["linux"]
+++

For this guide we'll be using `tmux`. To get started, run the `tmux` command in your terminal. You terminal should look like

![linux bad run ubuntu]({{< static "post-img/linux-tmux-terminal.png" >}})

Now inside of the tmux session run the playit program

```
./playit-linux_64-{{< latest-version >}}
```

If you're unable to run the playit program see 
* {{< link "run-on-linux" >}}


With the playit program now running you can use the following keyboard combinations

* `Ctrl-b + d` to put the tmux session in the background
* `Ctrl-b + c` to create a new window to run another program (like the Minecraft Server)
* `Ctrl-b + 0` to view the first window, similary `Ctrl-b <num>` will let you go between windows

If you press `Ctrl-b + d` and put the tmux session in the background, you can always get it back by running the command

```
tmux attach
```
