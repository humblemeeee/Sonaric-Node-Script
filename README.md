## VPS Requirements

|                | Minimal                  | Recommended                  |
|----------------|--------------------------|------------------------------|
| **RAM**        | 4 GB RAM                 | 8 GB+ RAM                    |
| **CPU Cores**  | 2 CPU cores              | 4+ CPU cores                 |
| **Disk Space** | 20 GB free disk space    | 100 GB+ free disk space (SSD)|
| **Architecture** | amd64 CPU Architecture | amd64 CPU Architecture       |
| **Operating System** | Ubuntu 22.04       | Ubuntu 22.04                 |

- You can buy VPS from [PQ Hosting](https://pq.hosting/en/vps) using Crypto
## Installation


https://github.com/user-attachments/assets/5e098b04-20ff-47ee-adb1-10c5db58de20
- Open Termius or Putty
- Use these 2 commands first to create a Screen session
```bash
sudo apt-get update
sudo apt-get install screen
```
```bash
screen -S Sonaric-Node
```
- Then Paste this command :
```bash
wget https://raw.githubusercontent.com/dxzenith/Sonaric-Node-Script/main/sonaric.sh && chmod +x sonaric.sh && ./sonaric.sh
```
- To detach from this screen u need to press `Ctrl + A + D`
- After that you can close your Termius or Putty App
