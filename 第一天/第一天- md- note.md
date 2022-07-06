# 第一天
## 认识vim的两种模式
- normal 模式 是vim操作模式 光标为块状
- insert 模式 是常规输入方式 

## 模式切换
### insert -> normal
- `jj` 进入normal模式
```
 "vim.insertModeKeyBindings": [
    {
        "before": ["j", "j"],
        "after": ["<Esc>"]
    }
],
```
> 之前课程中的进入normal模式为 `Ctrl + [` 并且需要改键 将 `caps lock` 替换 `左Ctrl` 后面觉得麻烦并未替换
### normal -> insert
- `i` 在光标前方输入
- `a` 在光标后方输入

## 移动方式
- `h` 向左移动
- `l` 向右移动
- `j` 向下移动
- `k` 向上移动

> 常用按键修改配置
```
"vim.useCtrlKeys": true,
"vim.handleKeys": {
    "<C-a>": true,
    "<C-s>": false,
    "<C-w>": false,
    "<C-z>": false,
    "<C-c>": false,
    "<C-x>": false,
    "<C-v>": true
},
```
