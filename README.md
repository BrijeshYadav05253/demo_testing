 2023  sudo chmod -R 755 /var/lib/gitea/ /etc/gitea/ /usr/local/bin/gitea
 2024  cat /etc/passwd | grep gitea
 2025  sudo chsh -s /bin/bash gitea
 2026  sudo systemctl daemon-reload
 2027  sudo systemctl restart gitea
 2028  sudo chown -R gitea:gitea /home/gitea/ /var/lib/gitea/ /etc/gitea/ /usr/local/bin/gitea
 2029  sudo mkdir -p /var/lib/gitea/data /var/lib/gitea/repositories
 2030  sudo chown -R gitea:gitea /var/lib/gitea /etc/gitea /usr/local/bin/gitea
 2031  sudo chmod -R 755 /var/lib/gitea /etc/gitea /usr/local/bin/gitea
 2032  sudo systemctl daemon-reload
 2033  sudo systemctl enable gitea
 2034  sudo systemctl start gitea
 2035  sudo systemctl status gitea
