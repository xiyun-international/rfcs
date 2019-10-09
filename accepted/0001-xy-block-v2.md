# 摘要

区块 2.0 版本，开发区块平台类似于飞冰界面，界面右侧点击区块下载即可复制命令。

# 动机

当前 xy 的区块（block）除了可以重复添加区块，还需要把多个区块做为一个合集，来快速添加。这样又能够把分散的区块整合到一起使得能够通过它们快速的初始化一个页面。

### 区块合集

区块合集的配置项，放在 package.json 或者 .xyrc 文件中。

```json
// package.json | .xyrc
{
  "blockConfig": {
    // 区块名称
    "name": "xy-antd-list",
    // 区块标题
    "title": "禧云通用列表页",
    // 区块分类
    "categories": [
      "信息展示"
    ],
    // 区块截图
    "screenshot": "http://f2.xiyunerp.com/face_access_logo.jpg",
    // 区块版本
    "version-0.x": "1.0.0"
    // 区块集合
    "blocks": {
      "BlockA": "https://github.com/xiyun-international/template/block/B",
      "BlockB": "https://github.com/xiyun-international/template/block/B",
    },
  }
}
```

执行命令即可安装区块集合。

```bash
xy block --collection 
```
