为了帮助同事的朋友的小孩完成大学选修课作业，故写了这个工程。

### 需求：

用python抓取腾讯视频网站上的视频，并转化为mp4。

### 参考大神的文章：

[https://blog.csdn.net/jia666666/article/details/82466553](https://blog.csdn.net/jia666666/article/details/82466553)

### 大体思路

1. 使用“https://jx.618g.com”解析腾讯视频，并分析ts视频源数量及路径
2. 使用requests.get下载ts视频
3. 使用copy将ts文件合并为一个mp4
