# 这是一个专注于分享知识笔记的平台
## A platform dedicated to knowledge and note sharing

## 仓库类目
### 计算机类
仓库:
- [focusnote/cs-basic](https://github.com/focusnote/cs-basic) <a href="javascript:void(0);" onclick="copyLink('https://github.com/focusnote/cs-basic')">📋 点击复制链接</a>
/基础通识<br>
主要内容为：高等数学、线性代数、概率论与数理统计、离散数学等。
- [focusnote/cs-core](https://github.com/focusnote/cs-core) <a href="javascript:void(0);" onclick="copyLink('https://github.com/focusnote/cs-core')">📋 点击复制链接</a>
/核心理论<br>
主要内容为：数据库原理、计算机组成原理、操作系统、数据结构与算法、编译原理、计算机网络等。
- [focusnote/cs-dev](https://github.com/focusnote/cs-dev) <a href="javascript:void(0);" onclick="copyLink('https://github.com/focusnote/cs-dev')">📋 点击复制链接</a>
/应用开发<br>
主要内容为：前端开发、后端开发、移动应用开发、游戏开发等。
- [focusnote/cs-ai](https://github.com:focusnote/cs-ai)
/人工智能<br>
主要内容为：机器学习、深度学习、自然语言处理、计算机视觉等。
- [focusnote/cs-bigdata](https://github.com/focusnote/cs-bigdata)
/大数据<br>
主要内容为：大数据技术、数据挖掘、数据仓库等。
- [focusnote/cs-iot](https://github.com/focusnote/cs-iot)
/嵌入式<br>
主要内容为：物联网原理、传感器技术、嵌入式系统等。
- [focusnote/cs-sec](https://github.com/focusnote/cs-sec) <a href="javascript:void(0);" onclick="copyLink('https://github.com/focusnote/cs-sec')">📋 点击复制链接</a>
/信息安全<br>
主要内容为：网络安全、信息安全管理、密码学等。

---

<script>
function copyLink(url) {
  if (navigator.clipboard && navigator.clipboard.writeText) {
    navigator.clipboard.writeText(url).then(function() {
      alert('链接已复制到剪贴板: ' + url);
    }).catch(function(err) {
      fallbackCopyTextToClipboard(url);
    });
  } else {
    fallbackCopyTextToClipboard(url);
  }
}

function fallbackCopyTextToClipboard(text) {
  var textArea = document.createElement('textarea');
  textArea.value = text;
  textArea.style.top = '0';
  textArea.style.left = '0';
  textArea.style.position = 'fixed';
  document.body.appendChild(textArea);
  textArea.focus();
  textArea.select();
  try {
    var successful = document.execCommand('copy');
    var msg = successful ? '成功' : '失败';
    alert('链接复制' + msg + ': ' + text);
  } catch (err) {
    alert('复制失败，请手动复制: ' + text);
  }
  document.body.removeChild(textArea);
}
</script>
