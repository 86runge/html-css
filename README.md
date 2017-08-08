# runge

核心知识

1.Git和GitHub

常见的工具的使用， 对比工具：Beyond Compare 3; 可视化工具：SourceTree，gitk

2.HTML5和CSS3 布局和样式

1).HTML5

新增标签：

  (1).新元素 canvas 画布  标签定义图形，比如图表和其他图像。该标签基于 JavaScript 的绘图 API

    <canvas> 标签通过脚本（通常是 JavaScript）来绘制图形（比如图表和其他图像）。
    <canvas> 标签只是图形容器，您必须使用脚本来绘制图形。
    属性：width(规定画布的宽度),height(规定画布的高度)

    <a href="https://github.com/86runge/runge/blob/master/html/canvas.html">通过 <canvas> 元素来显示一个红色的矩形</a>

  (2).新的多媒体元素

  audio 定义音频内容

    <audio> 标签定义声音，比如音乐或其他音频流。
    目前，<audio> 元素支持的3种文件格式：MP3、Wav、Ogg。
    属性：
    属性          值         描述
    autoplayNew   autoplay  如果出现该属性，则音频在就绪后马上播放。
    controlsNew   controls  如果出现该属性，则向用户显示音频控件（比如播放/暂停按钮）。
    loopNew       loop      如果出现该属性，则每当音频结束时重新开始播放。
    mutedNew      muted     如果出现该属性，则音频输出为静音。
    preloadNew    auto,metadata,none 规定当网页加载时，音频是否默认被加载以及如何被加载。
    srcNew        URL       规定音频文件的 URL。

    <a href="https://github.com/86runge/runge/blob/master/html/audio.html">通过 <canvas>播放声音：</a>

  video 定义视频（video 或者 movie）

    <video> 标签定义视频，比如电影片段或其他视频流。
    目前，<video> 元素支持三种视频格式：MP4、WebM、Ogg。
    属性：
    属性             值       描述
    autoplayNew   autoplay    如果出现该属性，则视频在就绪后马上播放。
    controlsNew   controls    如果出现该属性，则向用户显示控件，比如播放按钮。
    heightNew     pixels      设置视频播放器的高度。
    loopNew       loop        如果出现该属性，则当媒介文件完成播放后再次开始播放。
    mutedNew      muted       如果出现该属性，视频的音频输出为静音。
    posterNew     URL         规定视频正在下载时显示的图像，直到用户点击播放按钮。
    preloadNew    auto,metadata,none  如果出现该属性，则视频在页面加载时进行加载，并预备播放。如果使用 "autoplay"，则忽略该属性。
    srcNew        URL         要播放的视频的 URL。
    widthNew      pixels      设置视频播放器的宽度。

    <a href="https://github.com/86runge/runge/blob/master/html/video.html">通过 <canvas>播放录像：</a>

  source  定义多媒体资源 video 和 audio

    <source> 标签为媒体元素（比如 <video> 和 <audio>）定义媒体资源。
    <source> 标签允许您规定两个视频/音频文件共浏览器根据它对媒体类型或者编解码器的支持进行选择。
    属性：
    属性        值             描述
    mediaNew  media_query   规定媒体资源的类型，供浏览器决定是否下载。
    srcNew    URL           规定媒体文件的 URL。
    typeNew   MIME_type     规定媒体资源的 MIME 类型。
              (video/ogg,video/mp4,video/webm,audio/ogg,audio/mpeg)

    ```html
    <audio controls>
      <source src="horse.ogg" type="audio/ogg">
      <source src="horse.mp3" type="audio/mpeg">
      您的浏览器不支持 audio 元素。
    </audio>
    ```

  embed 定义嵌入的内容，比如插件。
  track 为诸如 video 和 audio 元素之类的媒介规定外部文本轨道。

  (3).新的表单元素

  datalist  定义选项列表。请与 input 元素配合使用该元素，来定义 input 可能的值。
  keygen  规定用于表单的密钥对生成器字段。
  output  定义不同类型的输出，比如脚本的输出。

  (4).新的标签元素

  article  定义页面独立的内容区域。
  aside  定义页面的侧边栏内容。
  bdi  允许您设置一段文本，使其脱离其父元素的文本方向设置。
  command  定义命令按钮，比如单选按钮、复选框或按钮
  details  用于描述文档或文档某个部分的细节
  dialog   定义对话框，比如提示框
  summary  标签包含 details 元素的标题
  figure   规定独立的流内容（图像、图表、照片、代码等等）。
  figcaption   定义 figure  元素的标题
  footer   定义 section 或 document 的页脚。
  header   定义了文档的头部区域
  mark   定义带有记号的文本。
  meter  定义度量衡。仅用于已知最大和最小值的度量。
  nav  定义导航链接的部分。
  progress   定义任何类型的任务的进度。
  ruby   定义 ruby 注释（中文注音或字符）。
  rt   定义字符（中文注音或字符）的解释或发音。
  rp   在 ruby 注释中使用，定义不支持 ruby 元素的浏览器所显示的内容。
  section  定义文档中的节（section、区段）。
  time   定义日期或时间。
  wbr  **规定在文本中的何处适合添加换行符。**

  ![html5新标签的结构图](https://github.com/86runge/runge/blod/master/html/target.html)
  ![html5新标签的结构图](https://github.com/86runge/runge/blod/master/img/html5.jpg)
  ![baidu](http://www.baidu.com/bdlogo.jif)

2).css3
