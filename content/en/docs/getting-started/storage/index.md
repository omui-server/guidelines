---
title: "Storage"
weight: 12
---

# Storage

Please place your data in the following directory:

- `$HOME` (`/home/$USER/`, `~/`)
  - 29TB in total
  - `$HOME/docker_rootless` is for Docker images and containers

> [!WARNING]
> Currently, there is no quota, but we may apply some restrictions on large capacity usage in the future.

## Copy your data

> [!WARNING]
> **OMUI Server storage is not intended for long-term use.**
> Please keep the original data externally (e.g., in the servers or PCs in each research groups).
> Please copy only the data you need to the OMUI Server storage, and delete data when it is no longer needed.

You can copy your data from your client PCs to OMU Server by using `scp` command:

```bash
$ scp [SRC] [username]@172.26.59.40:[DST]
```

> [!NOTE]
> You can recursively copy directories with `-r` option.

## Check your usage

You can easily check your storage usage with `ncdu` command.
Press `q` to quit.