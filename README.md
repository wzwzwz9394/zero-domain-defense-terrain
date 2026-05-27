# 零域方阵 Terrain

一个从 `zero-domain-defense-next` 复制出来的地形重构版。原项目保留为稳定版本，本项目专门用于继续改进地图、特殊地形和关卡设计。

## 在线游玩

线上地址：

```text
https://wzwzwz9394.github.io/zero-domain-defense-terrain/
```

这个项目不需要后端服务器。仓库的 Settings -> Pages 已配置为 GitHub Actions，每次推送到 `main` 分支都会自动发布。

后续地形、美术、手感和平衡性改进都在这个 Terrain 项目上继续。

当前版本包含普通防守和无尽挑战两种模式。只有无尽挑战会要求昵称，并按“地图 + 强度”保存浏览器本地前十排行榜。

当前重构重点是特殊地形：我方阵地可以建塔并获得加成；敌方路段会增强怪物，且不可建造炮塔。20 张地图都有主题化地形布局。

节奏机制包括波次准备倒计时、倒计时结束自动开波、无尽阶段强化，以及炮塔一键升满队列。

无尽模式加入炮塔终极改造：Lv.3 炮塔可以投入高额资金进行终局强化，每种塔都有不同的质变效果。

## 本地预览

```bash
python3 -m http.server 5174
```

然后打开：

```text
http://localhost:5174/zero-domain-defense-terrain/
```
