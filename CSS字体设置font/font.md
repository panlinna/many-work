###CSS字体设置font
1.Web Safe fonts---Web安全字体
2.自制font-face
  可以把字体库添加到自己的源码中，然后在CSS文件中添加：
  @font-face {
    font-family: "UniversLTStd";
    font-style: normal;
    font-weight: 300;
    src: url(/fonts/UniversLTStd-UltraCn.woff) format("woff")
}
这样就可以使用字体 UniversLTStd 了。
3.中文字体网址：http://www.youziku.com    http://font-spider.org/
