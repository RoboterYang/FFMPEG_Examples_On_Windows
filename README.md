# FFMPEG_Examples_On_Windows
FFmpeg 是一个集录制、转换、音/视频编码解码功能 为一体的完整的开源解决方案。FFmpeg 的开发是基于 Linux 操作系统,但是可以在大多数操作系统中编译和使用。
FFmpeg工具

ffmpeg : Fast forword mpeg
音视频转换器转换多媒体文件之间的格式的一个命令行工具
ffserver : Fast forword server
用 ffmpeg 实现的 rstp 服务器 基于 HTTP、RTSP 用于实时广播的串流服务器
ffplay : Fast forword play
一个简单的媒体播放器使用ffmpeg解析和解码通过SDL显示
ffprobe : Fast forword probe
一个多媒体流分析工具 它从多媒体流中收集信息 并且以人类和机器可读的形式打印出来
为开发者准备的库

核心工具libavutil
包含工具函数，用于存放内存操作等常用模块。
工具库,它包含函数简化编程,包括随机数生成器、数据结构、数学例程,核心多媒体工具,等等。
编解码libavcodec
用于存放各个 encode/decode 模块
一个包含了所有 FFmpeg 音视频编解码器的库.
媒体格式libavformat
用于存放 视音频复用器（muxer）/demuxer 模块
一个包含了所有的普通音视格式的打包和解包的库
设备libavdevice
读取电脑（或者其他设备上）的多媒体设备的数据 或者输出数据到指定的多媒体设备上
后处理
libavfilter
包含媒体滤波器的一个库
libswscale
执行高度优化的图像缩放和颜色空间/像素格式转换操作的库
libswresample
用于音频采样采样数据（PCM）的转换
摘自简书 https://www.jianshu.com/p/e41f6860fa5f
推荐大佬：https://www.cnblogs.com/wanggang123 这位大佬提供有非常优秀的资源，初学者或者研究的都可以去看看
