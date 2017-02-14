# Music Taster
顾名思义,这个项目用来挖掘音乐风格
大部分是基于歌单进行的关系挖掘,暂不涉及音频分析

### 动机
网易云音乐的红心歌单曲目太多了,想做点归类

## 目录结构
1. models——用于存储数据类型对象的相关类文件
2. utils——基本的工具类
3. pipelines——存放各工作流程的脚本

## 环境需求
1. 在工程根目录添加`db_config.json`文件,作为数据库IP:PORT信息的来源
2. 需要一个MongoDB实例进行数据管理
3. 必要时需要更换`cloudmusic_api.py`中的`csrf_token`(目测不需要该参数)

## 使用MIT License
