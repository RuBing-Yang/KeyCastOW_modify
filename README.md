### Note

**Forked from [brookhong/KeyCastOW](https://github.com/brookhong/KeyCastOW)**

A simple change:

Not create new message while keep mouse wheel scrolling

Reason:

I usually use *KeyCastOW* for presentations or meetings, and when i keep my mouse wheel scrolling up or down to turn pages, the messages would quickly cover the full screen. Then my content would be blocked, that’s kind of inconvenient. 

Compare：

<center>before：<img src="https://umeta.oss-cn-beijing.aliyuncs.com/blog/%E5%BD%95%E5%88%B6_2022_05_09_18_13_07_646_Moment.jpg" alt="录制_2022_05_09_18_13_07_646_Moment" width=25% /> &nbsp&nbsp after：<img src="https://umeta.oss-cn-beijing.aliyuncs.com/blog/%E5%BD%95%E5%88%B6_2022_05_09_18_10_29_243_Moment.jpg" alt="录制_2022_05_09_18_10_29_243_Moment" width=25% /> </center>


## build

```shell
msbuild /p:platform=win32 /p:Configuration=Release
```

Just run:  [keycastow.exe](keycastow.exe)  （on Windows）

## License

MIT License

Copyright © [2015 Brook Hong](https://brookhong.github.io/)

Forked from [brookhong/KeyCastOW](https://github.com/brookhong/KeyCastOW)
