# Ros_Go1

## 直接下载完整压缩包

[下载完整备份（1.31 GB）](https://github.com/yuening0819/Ros_Go1/releases/download/backup-20261102/VINS-Nav_Full_Backup_20261102.tar.gz)

已在 GitHub 服务器合并并通过 SHA-256 校验，下载此单个文件即可，无需手动合并。

Go1 录制、相机校正与离线建图项目完整备份。

## 分卷备用下载

[打开完整备份 Release](https://github.com/yuening0819/Ros_Go1/releases/tag/backup-20261102)。因网络中断风险，1.31 GB 原压缩包分为 20 个分卷上传，合并后与原包逐字节一致。

如需使用备用分卷：下载 Release 中的 `restore_backup.py` 到一个空文件夹，然后执行：

```bash
python3 restore_backup.py --download
tar -xzf VINS-Nav_Full_Backup_20261102.tar.gz
```

脚本会自动下载各卷，校验 SHA-256 并恢复原压缩包；不会自动解压或覆盖已有的不同内容文件。也可手动下载全部分卷后运行 `python3 restore_backup.py`。

备份包含源码、录像、标定资料、地图数据库、建图网页和项目内已有的第三方二进制依赖。解压后阅读 `BACKUP_README.txt`。

最新对比网页：`VINS-Nav/go1/mapping/20261102_video5_full_comparison/index.html`。单目结果仅供实验查看，没有真实米制尺度，不能直接用于导航。
