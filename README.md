# scelParser
搜狗输入法词库解析

### 使用
```
from scelParser import scel_parser

# 从文件
words = scel_parser.parse_file('热门游戏.scel')
print(words)

# 从数据
with open('热门游戏.scel') as f:
    words = scel_parser.parse(f.read())
print(words)
```

### 其他
[百度词库解析](https://github.com/Pingze-github/bdictParser)

### 说明
借鉴了[gamelife1314/scel2txt](https://github.com/gamelife1314/scel2txt)。允许从数据流获取。
