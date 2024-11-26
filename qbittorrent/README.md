# Default user

Default credentials should be `user: admin, password: adminadmin`. If it doesn't work, follow these steps [reference](https://www.reddit.com/r/unRAID/comments/180ou0b/psa_if_you_cant_login_to_qbittorrent_pass/):

1. Add the following to `qBittorrent.conf` under `[Preferences]`: `WebUI\Password_PBKDF2="@ByteArray(ARQ77eY1NUZaQsuDHbIMCA==:0WMRkYTUWVT9wVvdDtHAjU9b3b7uB8NR1Gur2hmQCvCDpm39Q+PsJRJPaCU51dEiz+dTzh8qbPsL8WkFljQYFQ==)"`
2. Restart docker
3. If it doesn't work, it's possible docker is recreating config file, work around that issue.
