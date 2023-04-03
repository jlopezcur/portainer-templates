# Portainer Templates

Using [linuxserver.io](https://www.linuxserver.io/) (when available).

## Quick start

1. Login to your portainer setup go to settings
2. Enable Use external templates
3. Add the url: https://raw.githubusercontent.com/jlopezcur/portainer-templates/master/template/template.json then go to app templates and hit refresh at the top.

## Ports mapping

- 8080: Homepage (Homer)
- 8081: Books (Kavita)
- 8082: Movies/Series (Jellyfin)
  - 7878: Radarr
  - 8989: Sonarr
  - 9117: Jackett
  - 8091: qBitTorrent
- 8083: Music (Navidrome)
- 8084: Cloud (NextCloud)

## App List

- [Homer](https://github.com/bastienwirtz/homer)
- [Kavita](https://github.com/Kareadita/Kavita)
- [Stump](https://github.com/aaronleopold/stump)
- [Jellyfin](https://github.com/jellyfin)
  - [Radarr](https://github.com/Radarr/Radarr)
  - [Sonarr](https://github.com/Sonarr/Sonarr)
  - [Jackett](https://github.com/Jackett/Jackett)
  - [qBitTorrent](https://github.com/qbittorrent/qBittorrent)
- [navidrome](https://github.com/navidrome/navidrome)
- [nextcloud](https://github.com/nextcloud)
- [audiobookshelf](https://github.com/advplyr/audiobookshelf)

## Where is the configuration?

All the configuration files is under the path `/portainer/apps/*/config` and
other metadata and stuff like that is also under the same structure.

## References

- https://github.com/Qballjos/portainer_templates
