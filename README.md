# Intro Skipper - Docker mod for Jellyfin

This Docker mod adds Intro Skipper to Jellyfin.

In Jellyfin's Docker arguments, set an environment variable `DOCKER_MODS=ghcr.io/alistairporter/docker-mod-jellyfin-introskipper`.

When adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ghcr.io/alistairporter/docker-mod-jellyfin-introskipper|linuxserver/mods:jellyfin-jellyfin-opencl-intel`
