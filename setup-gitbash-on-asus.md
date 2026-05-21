Guided by 
[Asus development](https://chatgpt.com/g/g-p-696d52a97c6c81919c0873238898cc21-asus-development/project) project on ChatGPT
See [the chat](https://chatgpt.com/share/69e93d9f-b56c-838b-9318-9f72c10d7e5a)

```bash
git config --global user.name "Scott Syme"
git config --global user.email "scsyme@gmail.com"
git config --global init.defaultBranch main
git config --global pull.rebase false
git config --global core.autocrlf true
```
======
```bash
ssh-keygen -t ed25519 -C "scsyme@gmail.com"
```
======
```bash
cat ~/.ssh/id_ed25519.pub | clip
```
======

Paste into GitHub SSH
in GitHub go to Settings → SSH and GPG keys → New SSH key and paste it there. GitHub says to add a descriptive title and paste the key into the key field.

======
```bash
ssh -T git@github.com
```
======
```bash
git clone git@github.com:scsyme/riverbank-tales-vault.git
```
======




