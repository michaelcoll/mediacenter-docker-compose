# mediacenter-docker-compose

Docker compose descriptor for my media center.

## The UID used for each app installed

| App          | UID  |
| ------------ | ---- |
| Plex         | 1002 |
| Transmission | 1003 |
| Radarr       | 1004 |
| Sonarr       | 1005 |
| MineOS       | 1007 |
| Tautulli     | 1009 |
| Prowlarr     | 1010 |
| Oveseerr     | 1012 |
| Homarr       | 1013 |
| Tdarr        | 1014 |

## The port used by each app installed

| Port  | App                    |
| ----- | ---------------------- |
| 5055  | Overseerr              |
| 7575  | Homarr                 |
| 7878  | Radarr                 |
| 8181  | Tautulli               |
| 8265  | Tdarr WebUI            |
| 8266  | Tdarr Server Port      |
| 8543  | MineOS                 |
| 8989  | Sonarr                 |
| 9091  | Transmission           |
| 9696  | Prowlarr               |
| 25565 | MineOS (TCP/UDP)       |
| 51413 | Transmission (TCP/UDP) |
