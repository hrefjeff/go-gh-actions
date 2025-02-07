```bash
# Install Docker on a VM
sudo apt-get update && sudo apt-get install docker.io -y && sudo systemctl start docker && sudo chmod 666 /var/run/docker.sock && sudo systemctl enable docker && docker --version
```

https://docs.github.com/en/actions/hosting-your-own-runners/managing-self-hosted-runners/configuring-the-self-hosted-runner-application-as-a-service

```bash
sudo ./svc.sh install
sudo ./svc.sh start
```
