disqus:

# 编辑前须知

### 如果您不能保证熟练掌握Github的操作，请直接联系QQ3530235993来贡献编辑

感谢您能够为 **MO Wiki** 做出贡献！

不过在开始之前，我们需要您了解并熟知 [帮助我们编辑页面](./intro/htc.md) 里的内容，以避免在编辑时产生不必要的麻烦。

最后重申重要的事：

- 请保证您的修改**格式正确**。
- 标题：本次 PR 的目的（做了 **什么** 工作，修复了 **什么** 问题）。
- 请备注**所有被您改动的文件**。包括您新建的文件夹和文件。如果新建了页面，应当改动 mkdocs.yml，此时也应当备注 `mkdocs.yml` 字样。

在阅读完之后，请点击下方的按钮，然后开始编辑。

<a id="btn-startedit" style="padding: 0.75em 1.25em; display: inline-block; line-height: 1; text-decoration: none; white-space: nowrap; cursor: pointer; border: 1px solid #6190e8; border-radius: 5px; background-color: #6190e8; color: #fff; outline: none; font-size: 0.75em;">开始编辑</a>

<script>
	function getQueryVariable(name, dft)
	{
		var reg = new RegExp('(^|&)' + name + '=([^&]*)(&|$)', 'i');
		var r = window.location.search.substr(1).match(reg);
		if (r != null)
		{
			return unescape(r[2]);
		}
		return dft;
	}
	document.getElementById("btn-startedit").href = "https://github.com/huanghaox1212/mot/edit/master/docs" + getQueryVariable("ref", "");
</script>