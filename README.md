# About project

- The repository contains 2 files.

1. .sh script file, which runs npm start
2. .service file, which is used to serve the .sh script

# Instructions

- Update project root directory path in .sh script

- Update path to node bin directory in .service

- Update (non-root) user in .service

- Update path to .sh script in service

# Usage

- Upload .service file to /etc/systemd/system

- Upload .sh script to somewhere in your server

- Reload Daemon buy running `sudo systemctl daemon-reload`

- Start service buy running `sudo systemctl start node-start.service`

- Check the status `sudo systemctl status node-start.service`