在线热更新的包放在这里，由源码仓库的 `node tools/hot_pub.mjs <test|stable> --site <本仓库目录>` 写入：

- `hot/test/manifest.json`、`hot/test/game.txt`：测试频道
- `hot/stable/manifest.json`、`hot/stable/game.txt`：稳定频道

包带签名，游戏里的加载器验过签名才会运行。不要手改这两个文件。
