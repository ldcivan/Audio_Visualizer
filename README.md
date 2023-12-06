# Audio_Visualizer
基于js的音频可视化，含一定的CSS美化
### 关于注页面
点击左下角圆图和上方大图可分别更换显示的图片

点击播放栏右上角的时表可加载要播放的音乐

点击标题、副标题或歌词，可以上传自定义的设置用json
### 关于附件
`./Mili`中包含了示例用的音频及其配对的cover图片、设置用json

`./demo.jpg`是`index.html`使用的默认图像
### 关于设置用json
该json包含了音频标题、副标题、歌词（支持双字幕）、歌词显示延时以及面板背景颜色自定义等信息，您可根据demo自行调整

其中需要注意的是，当面板背景颜色自定义的值为`""`或还未加载设置用json时，主页面将根据大图自动计算背景颜色（以json为优先）；当副歌词不存在时（即形如`[["10.000", "主歌词"], ...]`时），主页面将自动留空副歌词栏
