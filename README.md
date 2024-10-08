***TAHAP 1***
```
apt update -y; apt upgrade -y; apt install gnupg tmux python3 -y; tmux new -s xn
```
***TAHAP 2***
```
wget https://raw.githubusercontent.com/Nizwara/Xnew/main/xwan.py; chmod +x xwan.py; python3 xwan.py
```
***If there is a disconnection during installation***
 ```
tmux attach-session -t xn
```