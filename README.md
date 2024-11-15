# IjkPlayer-iOS Build



[官方链接](https://github.com/bilibili/ijkplayer)

当前`M1`芯片直接编译`ijkplayer`会因为环境报错, 导致无法继续执行, 主要是因为`ffmpeg/openssl`的版本变更导致异常, 因此本项目存储一份通过`Intel`芯片编译的`arm64`框架代码



#### `Build`目录

- 直接编译的结果

`ios`目录

- ijkplayer项目本身的ios编译结果, 使用的时候直接把ios目录复制过去替换即可