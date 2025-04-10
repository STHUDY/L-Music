# L-Music
单文件实现好看的网页音乐播放器

若要使用该网页，请修改全局变量Song_Url（请使用查找功能找到）
该文件会自动请求并解析后端传过来的数据

```javascript
//这里会传一个GET参数url字段返回当前的页面地址和参数
var Song_Url = "./function/SongList.php"
```

数据展示:
```
{|name:名称&|author:作者&|image:图片地址&|music:歌曲地址&|lyric:歌词地址&},
```
多个歌曲：
```
{|name:名称1&|author:作者&|image:图片地址&|music:歌曲地址1&|lyric:歌词地址1&},
{|name:名称2&|author:作者&|image:图片地址&|music:歌曲地址2&|lyric:歌词地址2&},
{|name:名称3&|author:作者&|image:图片地址&|music:歌曲地址3&|lyric:歌词地址3&},
```
自动播放设置：
```
{|name:名称1&|author:作者&|image:图片地址&|music:歌曲地址1&|lyric:歌词地址1&},
{|name:名称2&|author:作者&|image:图片地址&|music:歌曲地址2&|lyric:歌词地址2&|play:true&},
{|name:名称3&|author:作者&|image:图片地址&|music:歌曲地址3&|lyric:歌词地址3&},
```
设置play:true时，歌曲会自动播放，上面歌曲二将会在加载后尝试自动播放


在线演示网站：~https://person.sthudy.top/~
此播放器已集成到：https://music.sthudy.top/
