# Paperbox

 [**Demo**](http://sun11.me)
 
基于基于Landscape主题的Landscape-Plus主题由本人修改的主题，主要目的是自己使用，Hexo版本是3.1.1，nodejs 4.2.6

### 主题特性

- **纸张外观**
关于文章内容以外的东西只有几张纸和一个纸盒子（为了不那么无聊）

- **响应式设计**
最小宽度为320px，确保了在iPhone 4到5s的320x*分辨率的正常显示

- **诸多bug修复**
修复了包括archive分页显示，原主题在分享按钮、mobile nav界面、分页条等的诸多细节bug

### 对Landscape-Plus的功能修改

- **增加Swiftype站内搜索**
需在配置文件中设置`swiftype_key`

- **移除百度分享**
因为不明原因（可能是全局变量？）与Swiftype冲突，先执行的js功能正常，后执行的js会出问题，如百度分享的`更多`按钮点击无效

- **Landscape原主题分享增强**
将Pinterest更改为Linkedin，增加四个国内社交网站：微博，人人，QQ空间，微信

- **移除mathjax模块**
为了解决mathjax公式显示溢出问题，在主题自带的mathjax修改css没成功，但是使用hexo-math插件修改css成功，所以推荐使用hexo-math插件，主题内已包含修正的CSS样式

- **增加文章目录（TOC）显示**
需在文章中设置`toc: true`，默认不显示编号

### 浏览器支持

- **IE9+和目前版本的其它浏览器**