# SSH-Manager - SSH Connection Management Tool

A bash-based utility for managing and recording SSH connections across multiple systems.

## Overview

Simplifies SSH connection management by storing connection information, recording session activity, and providing a menu-driven interface for quick connections.

## Features

- Quick SSH connection launcher
- Automatic session recording
- IP address selection
- Server log management
- Connection history tracking

## Project Structure

```
.
├── ssh-manager.sh           # Main script
├── sshlog_selector.sh       # Log selection utility
├── recorder.sh              # Session recording
├── choose_ip.sh             # IP selection interface
├── get_interfaces.sh        # Interface detection
└── TODO.md                  # Pending improvements
```

## Usage

```bash
./ssh-manager.sh
```

## Status

Functional with planned enhancements (see TODO.md).

## Technologies

- Bash
- SSH/OpenSSH
