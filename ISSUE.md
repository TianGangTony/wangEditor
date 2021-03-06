# 问题记录

## 版本修复

### v3.0.1 

- [done] 如何设置自动增加高度（补充文档）
- [done] src/js/editor/Bar 改为 Progress，仅供上传图片使用
- [done] Panel 在右上角增加一个“关闭”按钮
- [done] 显示页面 table、quote、code 等样式，说明一下
- [done] 增加自定义上传回调函数，用以自定义返回图片的格式
- [done] 上传附带的参数，也加入到 form-data 中一份
- [done] 编辑器默认情况下，菜单栏不能点击，必须focus了编辑器求之后才能点击
- [done] 点击菜单弹出panel之后，再点击编辑器区域其他地方，panel不消失
- [done] 自定义filename，v2版本就有
- [done] ff 中的 bug
- [done] ff 中粘贴图片和文字出现问题 https://github.com/wangfupeng1988/wangEditor/issues/609
- [done] 火狐浏览器下，创建表格，编辑表格内容时，会出现两个控制点（有人提供了解决方案）
- [done] 配置最多上传的文件个数
- [done] 连续给两段内容 添加有/无序列表时，样式会出问题，且其他内容找不到了，并且编辑器不处于编辑状态。
- [done] onchange
- [done] IE11下面一直报错。并且表格无法正常使用

### v3.0.2

- [done] 用 onchange 完善 vue react 的 demo
- [done] 插入图片之后，光标移动到图片的前面，然后回车，图片消失，并且不能撤销
- [done] 修复上传图片 customInsert 无效的bug
- [done] 编辑区域 z-index 可配置
- [done] 上传图片不应该把状态码限制在 200，而是 2xx
- [done] editor.txt.html() 之后，没有定位光标位置

### 下次发版解决

- React-demo运行在IE11会卡顿，表格加载不出来
- list undo redo 有问题
- widows 下 word excel 的粘贴，存在垃圾数据
- IE 中粘贴的问题
- IE 中无法实现“引用”功能
- IE 中输入多行代码有报错

## 待排期

- 删除掉`./release`之后，执行`npm run release`会报错，原因是`fonts`文件没拷贝全，就要去替换`css`中的字体文件为`base64`格式，导致找不到文件。
- 针对编辑区域的`max-height`和`min-height`做一些处理，而且和全屏还不能通用
- 先点击'B'再输入内容这种形式，前期先支持 webkit 和 IE，火狐的支持后面再加上
- 公式
- 图片压缩 canvas https://github.com/think2011/localResizeIMG 
- github 徽章 https://github.com/EyreFree/GitHubBadgeIntroduction

