FROM tailscale/tailscale
ENV TS_AUTH_KEY=tailscale_key_required
ENTRYPOINT tailscaled && tailscale up --authkey=$TS_AUTH_KEY --accept-dns=false