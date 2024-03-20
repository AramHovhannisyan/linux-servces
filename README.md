# About project

- The repository contains 2 files.

1. bash script file, which runs `npm start`
2. service file, which is used to serve the bash script

# Instructions

- Update project root directory path in bash script

- Update path to node bin directory in service

- Update (non-root) user in service

- Update path to bash script in service

# Usage

- Upload service file to /etc/systemd/system

- Upload bash script to somewhere in your server

- Reload Daemon buy running `sudo systemctl daemon-reload`

- Start service buy running `sudo systemctl start node-start.service`

- Check the status `sudo systemctl status node-start.service`