.. _marked: https://github.com/chjj/marked
The fastest markdown parser in pure Python with renderer features,
inspired by marked_.

.. image:: https://img.shields.io/badge/donate-lepture-green.svg
   :target: https://typlog.com/donate?amount=10&reason=lepture%2Fmistune
   :alt: Donate lepture

### 万变不离其宗，请站在html的角度看markdown，其实一切很简单

<table><tr><td style="color:red">测试table标签数据</td></tr></table>
<p style="color:red">测试p标签数据，颜色渲染</p>

<p style="color:blue;" class="pte">标签测试</p>

<p style="color:blue;" onclick='alert("s")'>禁止click</p>

<font color="red">颜色</font>
<table><tr><td bgcolor=orange> 背景色是 1 orange</td></tr></table>
<link rel="stylesheet" type="text/css" href="theme.css" />
表情一：:+1:,表情二：:o:

    Group group = new Group();
		group.setId(id);
		if(groupService.deleteGroup(group)){
			return groupRoleService.deleteByGroupId(id);
		}

#### it seems markdown只支持部分html原生的属性设置写法，但不支持css以及style的部分写法；
<img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1533056743408&di=f6e17a49ae079daea6f0e2e4934d6026&imgtype=0&src=http%3A%2F%2Fimg3.duitang.com%2Fuploads%2Fitem%2F201509%2F14%2F20150914211622_EeJHY.jpeg" width="30px" height="30px"/>
