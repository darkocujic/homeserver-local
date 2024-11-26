# Home server setup

Complete home media and networking setup with config files and additional details. Uses mostly default settings while some services have their own configurations inside the service itself.

## Instructions

1. Enter a folder of a service `cd homepage`
2. Start services with `docker compose up -d`

Additional configurations might be available in each respective folder, use at will.

## Notices

- All timezones set to Europe/Zagreb, change it to your convenience according to [the list](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)
- Most services are ran as `uid=1000` and `gid=1000`

## References

- [DEV.TO Home media server with plex, sonarr, radarr, qbitorrent and overseerr](https://dev.to/rafaelmagalhaes/home-media-server-with-plex-sonarr-radarr-qbitorrent-and-overseerr-2a84)
