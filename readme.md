# motd
Made with code from [HermannBjorgvin/motd](https://github.com/HermannBjorgvin/motd) and [yboetz/motd](https://github.com/yboetz/motd)

1. `sudo git clone https://github.com/generalpask/motd.git /etc/update-motd.d`  
2. Disable motd in `/etc/pam.d/sshd`
3. Add `run-parts /etc/update-motd.d` to your `.bashrc` or `.zlogin`
