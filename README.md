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

# Kill port

npx kill-port 8080

```
