### Titan-Galileo-Testnet-Node ###

### Minimum Hardware Requirements: ###
CPU : 2c VPU
RAM : 2GB
Storage 50G SSD

Go to https://test4.titannet.io/
Connect wallet Kepler
Copas you key
Done

Install Snap (If you already install skip)
```
sudo apt update
sudo apt install snapd
```

Enable snap:
```
sudo systemctl enable --now snapd.socket
```

Install Multipass:
```
sudo snap install multipass
```

Download and Extract Installation Package:
```
wget https://pcdn.titannet.io/test4/bin/agent-linux.zip
```

Create directory:
```
mkdir -p /opt/titanagent
```

Extract package:
```
unzip agent-linux.zip -d /opt/titanagent
```

Masuk folder Titan:
```
cd /opt/titanagent
```

Run:
```
./agent --working-dir=/opt/titanagent --server-url=https://test4-api.titannet.io --key=<your-key>
```

Note:
Replace "your-key" with the key you

After run copas Node ID

Check status Agenr:
https://test4.titannet.io/nodeDetails

Search your node ID
Done

