# 云音乐全屏播放器

独立的全屏歌词显示页面，配合 [ha_ncloud_music](https://github.com/neqq3/ha_ncloud_music) 使用。

## 安装

1. 在 HACS 中添加自定义仓库：`https://github.com/neqq3/ha_ncloud_music_web`
2. 类别选择 **Dashboard**
3. 安装

## 使用

安装后访问：
```
http://<HA_IP>:8123/local/community/ha_ncloud_music_web/lyrics-player.html
```

## 配置参数

可通过 URL 参数自定义播放器行为：

| 参数 | 说明 | 示例 |
|------|------|------|
| `entity_id` | 媒体播放器实体 | `media_player.cloud_music` |

示例：
```
http://<HA_IP>:8123/local/community/ha_ncloud_music_web/lyrics-player.html?entity_id=media_player.cloud_music
```
