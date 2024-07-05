[English](README.md)|[简体中文](README_zh.md)

# ZEXIAT OPEN REPOSITORY
## 关于
zexiat是Sumilarise溯升团队开发的QQ机器人
本Bot基于Python Nonebot2 OpenShamrock PostgreSQL MuMu模拟器
+ Python版本: 3.9.6
+ NoneBot2版本: 2.1.3
+ OpenShamrock版本: Shamrock-v1.0.9.r429.2db187e-all
+ PostgreSQL版本: 14.4
+ MuMu模拟器版本:3.1.50

[About(与bot内about内容相同)](about.md)

## 这是什么
这是Zexiat Bot Beta版本的仓库


## 功能列表
懒得写


## Bot部署
### 环境需求
+ Python版本: 3.9.6(其余参考关于部分)

1.使用`pip install poetry`安装虚拟环境
**注意**:Python版本必须一致

2.进入程序根目录,使用`poetry install`安装依赖
**注意**:必须在程序根目录下

3.安装PostgreSQL,将数据库配置填入configs/config.py中

### 配置
.env.dev下的SUPERUSERS填入自己的qq(可以是多个)
configs/config.py填入
MMA_PATH
RESOURCE_GROUP
SUPERUSER

### 启动bot
运行程序根目录下的start.bat

## 鸣谢
1. 部分程序
   + [Python](https://www.python.org/)
   + NoneBot2:[Docs](https://nb2.baka.icu/) [Github](https://github.com/nonebot/nonebot2)
   + OpenShamrock:[Docs](https://yuyue-amatsuki.github.io/OpenShamrock/) [Github](https://github.com/whitechi73/OpenShamrock)
   + [PostgreSQL](https://www.postgresql.org/)
   + [MuMu模拟器](https://mumu.163.com/)
2. Nonebot插件
   + [早晚安](https://github.com/KafCoppelia/nonebot_plugin_morning)
   + [PicStatus](https://github.com/lgc-NB2Dev/nonebot-plugin-picstatus)
   + [MakeMidi(有修改)](https://github.com/RandomEnch/nonebot_plugin_makemidi)
   + [娶群友(有修改)](https://github.com/KarisAya/nonebot_plugin_groupmate_waifu)
   + 基于Diving-Fish的[mai-bot](https://github.com/Diving-Fish/mai-bot)(有修改)
   + [wordle(有修改)](https://github.com/noneplugin/nonebot-plugin-wordle)
   + [htmlrender](https://github.com/kexue-z/nonebot-plugin-htmlrender)
3. 开发者
   + [seven](https://github.com/SEVEN-6174):功能逻辑
   + [songelar](https://github.com/songelar):UI生成
   + Azithromycin:团队负责人

本项目所有权利由溯昇团队(2023-2024)保留