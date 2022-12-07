# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:ory-hydra_2.0.2_amd64.rock docker-daemon:ory-hydra:2.0.2
docker run ory-hydra:2.0.2
```
