# Ros_Go1

Go1 录制、相机校正与离线建图项目备份。

## 完整备份

请到 [完整备份 Release](https://github.com/yuening0819/Ros_Go1/releases/tag/backup-20261102) 下载 `VINS-Nav_Full_Backup_20261102.tar.gz`，以及同名 SHA-256 校验文件。

备份包含本地源码、录像、标定资料、地图数据库、建图结果和项目内已有的第三方二进制依赖。解压后阅读 `BACKUP_README.txt`。

```bash
sha256sum -c VINS-Nav_Full_Backup_20261102.tar.gz.sha256
tar -xzf VINS-Nav_Full_Backup_20261102.tar.gz
```

最新完整视频对比网页：解压目录中的 `VINS-Nav/go1/mapping/20261102_video5_full_comparison/index.html`。

这是项目文件备份，不是完整系统镜像；部分系统依赖仍需准备。单目建图结果是实验性特征投影，没有真实米制尺度，不能直接用于导航。
