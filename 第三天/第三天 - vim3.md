# 第三天
## vim语法
- 操作 + 范围
### 操作
- `d` 删除
- `c` 删除并进入insert模式
- `y` 复制
### 范围
- `e` 移动到单词的结尾
- `w` 移动到单词的开头
- `b` 移动到上一个单词的开头
```
hello world
```

### 组合
- `c + H` 删除光标之前的内容
- `c + L` 删除光标之后的内容
> H L 需要改键
```
hello world

"vim.operatorPendingModeKeyBindings": [
        {
            "before": ["H"],
            "after": ["^"]
        },
        {
            "before": ["L"],
            "after": ["g", "_"]
        }
    ]
```