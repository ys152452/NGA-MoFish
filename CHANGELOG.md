# 更新日志

## [1.5.3]

- 新增了点赞功能

## [1.5.2]

- 优化了搜索结果，过滤了无法查看的帖子

## [1.5.1]

- 增加了同步nga收藏节点的功能，感谢[ys152452](https://github.com/ys152452)的PR

## [1.4.17]

- 切换nga域名...

## [1.4.16]

- 更换了登录校验的地址

## [1.4.15]

- [Gaays](https://github.com/Gaays):还原nga域名并修改ua，解决无法查看评论的问题

## [1.4.14]

- [Gaays](https://github.com/Gaays):切换nga域名

## [1.4.13]

- 继续尝试修复解析json的问题

## [1.4.12]

- 修复了部分情况下json解析失败的问题

## [1.4.11]

- 修复了复制url时截取出错的bug

## [1.4.10]

- 优化了抓取nga的url

## [1.4.9]

- 右键菜单增加了标为已读功能

## [1.4.8]

- 修正了下一页应该出现的时机

## [1.4.7]

- 修正了取消只看楼主的逻辑

## [1.4.6]

- 修正了只看楼主的逻辑
- 修正了右键菜单中的[在浏览器中打开]

## [1.4.5]

- 增加了页面跳转

## [1.4.4]

- 增加了翻页功能， 每次可以展示最多5页的内容，避免因为帖子过长导致加载时间太久。

## [1.4.3]

- 增加了简单的搜索功能，目前仅限搜索前50个主题标题相关的有效内容，如果有更多需求我再加~

## [1.4.2]

- 现在可以在无图、小图、正常三个模式中进行切换了

## [1.4.1]

- 优化了复制链接功能，不会再带着后面那个js了

## [1.4.0]

- 修复了刷新会有重复帖子的情况

## [1.3.9]

- 优化了只看楼主、取消只看楼主出现的逻辑

## [1.3.8]

- 增加了已读帖子过滤的开关
- 增加了取消只看楼主的按钮（希望有大佬能优化成只显示一个的样式，能力有限了）
- 小图模式下，单击后会在原页面上放大显示

## [1.3.7]

- fix:已读列表帖子重复

## [1.3.6]

- 新增了只看楼主功能（感谢呦哥@Exceedingly0代码！）

## [1.3.5]

- 继续尝试修复mac上不能用的问题

## [1.3.4]

- 返回的json暗改了，修了一下不显示楼主的问题

## [1.3.3]

- 好像能在macos上面用了？

## [1.3.2]

- 是否显示AC娘变成了是否开启小图模式，点击小图可以查看大图，看看这样摸鱼体验会不会更好

## [1.3.1]

- 已读队列扩展到500，修正了队列进出逻辑
- 目前已知的Bug有：json无法序列化包含特殊字符的字符串，有时候引用不会正常显示

## [1.3.0]

- 可以显示前100个已读的帖子
- 可以调整每个分区显示帖子的最大数量了~

## [1.2.6]

- 加了一个是否显示AC娘表情的开关，但是nga的表情有的是表情格式，有的是img图片，只能关闭表情格式的那部分

## [1.2.5]

- 本版本对获取内容做了严格限制，只会显示该版内容，不会再显示子版内容，如有需要，需手动添加子版fid，请根据需求进行更新

## [1.2.4]

- 替换了图标
- 子板标题最大长度限制为5

## [1.2.3]

- 解决了一个神奇的BUG

## [1.2.2]

- 优化了一下显示

## [1.2.1]

- 可以看子分区标题了

## [1.2.0]

- 可以看AC娘表情了

## [1.1.3]

- 优化了解析引用的逻辑
- 添加了第一次使用的引导

## [1.1.2]

- 修复了没法用的bug

## [1.1.1]

- 修复了引用匿名的Bug
- 可能是nga的问题，有时候只有[quote]但是没有[/quote]，会影响显示效果

## [1.1.0]

- 可以打开指定的tid帖子了
- 修复了几个显示回复时的BUG
- 可以看贴条了

## [1.0.0]

- nga摸鱼插件