---
title: "datasets"
sidebar_label: "datasets"
pagination_prev: null
pagination_next: null
---

Lists datasets loaded by the Spice runtime

### Usage

```shell
spice datasets [flags]
```

#### Flags

- `--tls-root-certificate-file`   The path to the root certificate file used to verify the Spice.ai runtime server certificate
- `-h`, `--help`   help for datasets

### Examples:

```shell
>>> spice datasets

FROM                             NAME                      REPLICATION ACCELERATION DEPENDSON STATUS
spice.ai/eth.beacon.recent_slots eth_beacon_recent_slotsss false       false                  Ready
spice.ai/eth.recent_blocks       eth_rec_blocks            false       false                  Initializing
```
