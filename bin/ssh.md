# About SSH
Using the SSH protocol, you can connect and authenticate to remote servers and services.

# Generating a new SSH-Key

Open a Terminal or Git Bash

```sh
$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com
```

This creates a new ssh key, using the provided email as a label.

[source](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#platform-windows)