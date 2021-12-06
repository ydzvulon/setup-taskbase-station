# setup-taskbase-station
tasks to setup branch new developer environment



### SSH setup

> `origin:` https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

```yaml
tasks:
  create-ssh-key: ssh-keygen -t ed25519 -C "your_email@example.com"
  show-ssh-agent-start-cmd: eval "$(ssh-agent -s)"
  
