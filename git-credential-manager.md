
Installation
On WSL2 Ubuntu
```bash
git config --global --unset credential.helper

```

https://github.com/git-ecosystem/git-credential-manager/blob/release/docs/install.md#install-2

https://github.com/git-ecosystem/git-credential-manager/releases/download/v2.7.0/gcm-linux-x64-2.7.0.deb



```bash
cd ~/Downloads/installers

wget https://github.com/git-ecosystem/git-credential-manager/releases/download/v2.7.0/gcm-linux-x64-2.7.0.deb

sudo dpkg -i ~/Downloads/installers/gcm-linux-x64-2.7.0.deb
git-credential-manager configure
```

