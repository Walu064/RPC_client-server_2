# RPC_client-server_2

How it works? Every sign from STDIN is sent from process I (client) to process II (server). On the server-side every
single sign is converted to hex and saved to a file (filename - client PID).

## Installation:
Use this command to clone the repository on your linux device:
```bash
git clone https://github.com/Walu064/RPC_client-server_2
```

## Usage:
```bash
./app_server
#Now open the second terminal, go to project directory and write:
./app_client
```
If everything works fine, you will see client PID on the server-side. Now you can insert every sign you want on the
client-side (including white characters).

If you want put some changes in the codes of server or client, after performing it use Makefile. Just write:
```bash
make
```
in terminal. Every single actualization of code must be preceded by compilation.
