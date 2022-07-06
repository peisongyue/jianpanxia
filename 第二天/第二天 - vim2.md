# 第二天
## 掌握行相关的命令
- 移动至行首 移动至行尾  需改键
```
"vim.normalModeKeyBindings": [
        {
            "before": ["H"],
            "after": ["^"]
        },
        {
            "before": ["L"],
            "after": ["g", "_"]
        }
    ],
```
- `Ctrl + H` 移动至行首
- `Ctrl + L` 移动至行尾
```
hello world
```
## 插入方式
- `I` 行首插入
- `A` 行尾插入
- `O` 行上插入
- `o` 行下插入
```
hello world
```
## 行操作
- `dd` 整行删除 实际功能为剪切
- `yy` 整行复制
- `p` 黏贴