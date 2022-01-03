# infrastructure
Personal server infrastructure

Website: https://eridan.me/

Minecraft server (bridged):
- eridan.me:25565 for Java
- eridan.me:19132 for Bedrock

## Other things not listed or more info:

- `fast_commit` is enabled:

```
[root@honkmeow ~]# tune2fs -l /dev/nvme0n1p1 | grep features
Filesystem features:      has_journal ext_attr resize_inode dir_index fast_commit filetype needs_recovery extent 64bit flex_bg sparse_super large_file huge_file dir_nlink extra_isize metadata_csum
```

- Minecraft server uses libjemalloc instead of default malloc for performance
- honkmeow == karkat
