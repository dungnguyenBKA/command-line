# Useful Commands
This Markdown file contains various useful commands for SSH, VIM, getting the private IPv4 address, and killing a port. Let me know if there's anything else I can assist you with!




```bash
# VPS

ssh root@161.97.149.26
ssh -i key.pem azureuser@40.82.146.17

# SSH git

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/chavis

ssh -T git@github.com
ssh -T git@gitlab.com


# Copy all in vim to clipboard

ggVG "+y

# Get private IPv4

ipconfig getifaddr en0

# Git pull all sub dir

ls | xargs -I{} git -C {} pull

find . -mindepth 1 -maxdepth 1 -type d -exec sh -c 'echo "\033[1;33mUpdating {}\033[0m" && cd "{}" && git status' \;

# Kill port

npx kill-port 8080

```
