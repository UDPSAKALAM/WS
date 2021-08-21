# SocksProxy with Client Auto-Disconnect
## By Dexter Cellona Banawon

Installer : `bash -c "$(wget -qO- https://git.io/JEe46)"`

Updater   : `bash -c "$(wget -qO- https://git.io/JEJsm)"`

Download OpenVPN Config using the format:
  - `http://<IP or domain>/<IP>.ovpn`

### Ports:
  - 80 (SSH)
  - 8880 (OpenVPN)

### Downloads
  1. Put the files inside `/etc/socksproxy/web` directory.
  2. Restart `socksproxy` via `systemctl` command.

### Server Response Message
  1. Edit/Create `/etc/socksproxy/message` file.
  2. Restart `socksproxy` via `systemctl` command.

### Note: Use `xdcb` command to operate.
