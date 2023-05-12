# Rime
[鼠鬚管](https://rime.im/release/squirrel/)
[小狼毫](https://rime.im/release/weasel/)

⌨️Rime输入法配置

## 配置特点

- 主要使用小鹤双拼方案，兼顾明月拼音和容易英语方法。
- 主要使用鼠须管方案

## 配置文件
```
.
├── custom_phrase.txt                 # 自定义短语
├── default.custom.yaml               # 默认配置
├── double_pinyin_flypy.custom.yaml   # 小鹤双拼方案个人配置
├── double_pinyin_flypy.schema.yaml   # 小河双拼方案原始配置
├── easy_en.dict.yaml                 # easy en 方案词库
├── easy_en.schema.yaml               # easy en 原始配置
├── lua                               # lua 语言编写的特别键盘映射
│   ├── charset.lua
│   ├── date.lua
│   ├── expand_translator.lua
│   ├── number.lua
│   ├── reverse.lua
│   ├── single_char.lua
│   ├── switch.lua
│   └── time.lua
├── luna_pinyin.cn_en.dict.yaml
├── luna_pinyin.extended.dict.yaml
├── luna_pinyin.poetry.dict.yaml
├── luna_pinyin.sgmain.dict.yaml
├── opencc
│   ├── emoji.json
│   ├── emoji_category.txt
│   └── emoji_word.txt
├── squirrel.custom.yaml
└── user.yaml
```

## 参考

- [GitHub - scomper/Rime: 鼠须管配置](https://github.com/scomper/Rime)
