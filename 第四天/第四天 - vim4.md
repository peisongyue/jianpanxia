# 第四天
## 字符操作
### 单字符
- `x` 删除光标所在的字符 *
- `X` 删除光标前的字符 
- `s` 删除当前光标的字符并进入insert模式 *
- `S` 删除当前光标所在行并进入insere模式 *
- `r` 替换一个字符 *
- `R` 替换多个字符
```
we are the world
```
### undo/redo
- `u` undo
```
I don't know    ddddddhh
```
> 知识点 在undo中 可撤销块 是进入插入模式开始，知道返回普通模式为止，在此期间输入或删除的任何内容都被当成一次修改
>> 并不觉得有什么用 Ctrl + z 更方便


```
test
we are the world, we are the children
```