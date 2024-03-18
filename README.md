# CVE-2024-23334-PoC
A proof of concept of the path traversal vulnerability in the python AioHTTP library =&lt; 3.9.1

## Requirements
* **python3-venv**
> ```sudo apt install python3-venv```

## Lab setup
```bash
git clone https://github.com/z3rObyte/CVE-2024-23334-PoC
cd CVE-2024-23334-PoC
python3 -m venv .env
chmod +x ./.env/bin/activate
source ./.env/bin/activate
pip3 install -r requirements.txt
python3 server.py
```
## Exploit it!
You can use the exploit that comes in the repository:
```
bash exploit.sh
```
