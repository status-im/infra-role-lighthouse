# Description

This role deploys a [Lighthouse Beacon Node](https://lighthouse-book.sigmaprime.io).

# Configuration

```yaml
lighthouse_config_jwt_secret: '32-chars-secret-from-el-node'
lighthouse_config_checkpoint_sync_url: https://mainnet.checkpoint.sigp.io
lighthouse_cont_external_networks:
    - 'el-docker-network'
```
