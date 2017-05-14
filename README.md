# runge

核心知识

1.Git和GitHub
  
  常见的工具的使用， 对比工具：Beyond Compare 3; 可视化工具：SourceTree，gitk

2.HTML5和CSS3 布局和样式

  1).HTML5

    新增标签：
      canvas  标签定义图形，比如图表和其他图像。该标签基于 JavaScript 的绘图 API

        通过 <canvas> 元素来显示一个红色的矩形：
        <canvas id="myCanvas"></canvas>
         
        <script type="text/javascript">
        var canvas=document.getElementById('myCanvas');
        var ctx=canvas.getContext('2d');
        ctx.fillStyle='#FF0000';
        ctx.fillRect(0,0,80,100);
        </script>

      audio 定义音频内容
      video 定义视频（video 或者 movie）
      source  定义多媒体资源 video 和 audio
      embed 定义嵌入的内容，比如插件。
      track 为诸如 video 和 audio 元素之类的媒介规定外部文本轨道。

      datalist  定义选项列表。请与 input 元素配合使用该元素，来定义 input 可能的值。
      keygen  规定用于表单的密钥对生成器字段。
      output  定义不同类型的输出，比如脚本的输出。

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
      wbr  规定在文本中的何处适合添加换行符。
