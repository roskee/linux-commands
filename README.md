# linux-commands
A handy place to get that command you used a while ago but completely forgot :)

current support is for Ubuntu.

## disk
- check disk usage ( yeah - in human language! )
  ```shell
  df -h
  ```
- clean up systemd journal logs
  ```shell
  sudo journalctl --rotate // archive the logs to be non-writable
  sudo journalctl --vacuum-time=1s // delete the logs
  ```
