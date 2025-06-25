# HelixDocker

HelixDocker is a rootless, Docker-free container runtime designed for shared Linux servers. No Docker. No systemd. No root.

## Features
- Run isolated apps in containers
- CPU, RAM, and disk usage limits
- Volume mounts (host ↔ container)
- Full CLI control (like Docker)

## Usage

```bash
./helixdocker.py create myapp
./helixdocker.py run myapp
./helixdocker.py list
./helixdocker.py stop myapp
