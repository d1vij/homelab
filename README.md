My homelab stack with most of the stuff running on docker containers and proxied via cloudflared tunnnels

Current services include

| Name | Why | 
| --- | ---- |
| Cloudflared Tunnel | Acts as reverse proxy on my lan to expose local services on my domain (*.divij.xyz)|
| Obsidian Livesync | Sync for obsidian notes, runs a couchdb container which is accessed by `LiveSync` extension of Obsidian notes |
| Vault Warden | Self-hosted backend for Bitwarden |


