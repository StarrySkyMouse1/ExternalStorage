# ExternalStorage

外部存放仓库：用于托管不便放进主工程的大体积静态资源。

## Surf 地图封面（929 张）

- 来源包：`Surf-Map-Covers-929-20261122.zip`（929 张 JPG，约 359 MiB）
- 入库时间：2026-11-23
- 命名：`surf_<地图名>.jpg`，与地图 `canonical_name` 一致（如 `surf_666.jpg` ↔ `surf_666`）
- 单张体积：38 KB ~ 1.5 MiB，均远低于 GitHub 单文件 100 MB 上限，直接以普通 Git 对象存放，无需 Git LFS

### 直链引用

```
https://raw.githubusercontent.com/StarrySkyMouse1/ExternalStorage/main/surf_666.jpg
```

国内网络访问 `raw.githubusercontent.com` 不稳时，可改用 jsDelivr（同一文件、走 CDN）：

```
https://cdn.jsdelivr.net/gh/StarrySkyMouse1/ExternalStorage@main/surf_666.jpg
```

### 目录说明

封面文件全部位于仓库根目录，共 929 个 `.jpg`，无子目录；新增批次请沿用 `surf_<地图名>.jpg` 命名，避免重名覆盖。
