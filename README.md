# NMLab final project: Housing Agency System

## How to run the project?

## Server
It is needed to install some libraries on your computer in advance. (ex.numpy, ecdsa... )
First, we should open the control panel of servers.
```bash
$ cd control_panel
$ bash run.sh
```

Then open four terminal to run four servers (which should be set by real estate agents).
```bash
$ cd real_estate_agents
$ bash run1.sh
```
```bash
$ cd real_estate_agents
$ bash run2.sh
```
```bash
$ cd real_estate_agents
$ bash run3.sh
```
```bash
$ cd real_estate_agents
$ bash run4.sh
```

### Client
If the client and server are not on the same host, we should change the 'HOST' into server's fixed IP address in client/client.py
