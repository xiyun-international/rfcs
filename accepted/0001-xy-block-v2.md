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
    "blocks": {
      "BlockA": "https://github.com/xiyun-international/template/block/B",
      "BlockB": "https://github.com/xiyun-international/template/block/B",
    },
  }
}
```

执行命令即可安装区块集。

```bash
xy block --collection 
```
