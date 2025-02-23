# GTA3.Mobile.CHS
Better Chinese Translation of GTA III,VC,SA,LCS
# 汉化原理
拇指玩汉化中文以utf8表示，占用2个字节。由于日语刚好也是这种方式，所以直接替换日语文本。

met文件每一行开头是汉字的utf8编码 后面的大概4个坐标分别是图片里的x1 y1 x2 y2 也就是游戏通过met文件的坐标，确定图片中的汉字位置。然后渲染这个字。
