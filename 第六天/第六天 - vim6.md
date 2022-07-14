# 第六天 - vim06
掌握文本对象


## 练习

```js

function setName(_name) {
    name = _name

    const cxr = `cxr`
    const cxr = "cxr"
    const cxr = 'cxr'
}

obj["name"]

this is a juzi.
this is a juzi!
this is a juzi?

<div>this is a test for t</div>

```

## 知识点
- 认识文本对象 
- 语法 
  - operator + (内部/外部) + 文本对象
  - 可视化对象 + (内部/外部) + 文本对象
- 内部 `i`
- 外部 `a`
- 对象
  - `w` 一个单词
  - `(|)` 一对()
  - `b` 一对()
  - `[|]` 一对[]
  - `{|}` 一对{}
  - `B` 一对{}
  - `<|>` 一对<>
  - `t` XML标签
  - `'` 一对''
  - `"` 一对""
  - `\`` 一对``
  - `s` 一个句子
  - `p` 一个段落
  - vim-textobj-argunments 
    - `ia` 不包含分隔符
    - `aa` 包含分隔符
    - 技巧
      - 删除一个字符 daa
      - 修改一个字符 cia  