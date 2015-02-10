## Oh-my-zsh - Fancy your terminal

We will use the shell named `zsh` instead of `bash`, the default one.

```bash
$ sudo apt-get install zsh curl vim
$ curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh > install.sh
$ bash install.sh
$ rm install.sh
```

Be careful, those commands will ask you to type your password twice. At the end
your prompt should look like this:

![](images/ubuntu_oh_my_zsh.png)

If it doesn't, **ask a teacher**.

To make this change stick, restart your virtual machine:

```bash
$ sudo shutdown -r 0
```