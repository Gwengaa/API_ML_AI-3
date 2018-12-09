# 微信推文朗读小插件
## 一.产品需求文档
### 小结
- 加值宣言:通过调用百度语音合成API，将微信文章转换成音频朗读出来，以按钮的形式放置在文章标题下，提升读者阅读体验。除此之外还增加了推荐文章及最近阅读文章查看的功能。
- 核心价值：最小可用性产品是增加微信文章朗读功能，让用户能够用耳朵听文章。
- 用户痛点
	- 用户处在难以使用眼睛阅读的环境，需要借助耳朵来阅读
	- 微信公众号文章缺少朗读功能，有公众号自己录音，但成本较高。
	- 微信读书可以读公众号文章，但下载一个app对用户来说成本高，且动作繁杂，粘度不高
	- 因此本插件直接以按钮的形式放置在文章标题下朗读文章，解决了用户用耳朵听文章的需求
- 人工智能概率性：文章中有多音字时，会朗读错误的几率。但开发者可以实现标注多音字的发音，如：重(chong2)报集团。
	
- 需求列表

| Title  | User story |Importance |Notes|API|
| ------------- | ------------- |
| 用耳朵听推文 | 用户在公交车等人多晃荡的地方也能用耳朵获取文章内容  |重要|核心功能|[百度语音合成](http://ai.baidu.com/docs#/TTS-API/top)|
| 推荐文章  | 根据用户的阅读内容推荐相关或热门的文章 |次要|推荐系统|[WechatSogou](https://github.com/Chyroc/WechatSogou)|

> 有更多关于PRD部分，具体请点击[产品需求文档]((/PRD.md)

## 原型部分请参见：[PRD-原型.md](/PRD-原型.md)
## API部分请参见：[PRD-API.md](/PRD-API.md)

------
## 清单
- [PRD.md](/PRD.md)
- [PRD-原型.md](/PRD-原型.md)
- [PRD-API.md](/PRD-API.md)
- [代码-朗读功能](/read_article.ipynb)
- [原型文档](https://koujii.github.io/wechat_read_article/#g=1&p=%E6%9C%97%E8%AF%BB%E6%96%87%E7%AB%A0-%E7%95%8C%E9%9D%A2%E4%B8%8E%E4%BA%A4%E4%BA%92)


- 
