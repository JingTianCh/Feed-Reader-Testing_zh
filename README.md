## 项目预览

在这个项目中，你会得到一个基于 web 的用来读取 rss 源的应用。最开始的这个项目的开发者意识到了测试的价值，他们也已经把 [Jasmine](http://jasmine.github.io) 包含在了项目之中，提供了测试用例。

## 项目目的

测试是开发过程中一个很重要的部分，很多组织把一个标准的开发过程称之为测试驱动开发。意思就是开发人员在他们开始着手编写应用代码之前先写好测试用例。当然这个时候所有的测试用例都是通不过的，然后他们就开始编写应用代码使测试全部通过。
测试都是我们要掌握的一项重要技能。

## 已完成的项目
# 下载地址：https://github.com/JingTianCh/Feed-Reader-Testing_zh.git
# 运行：index.html 即可查看测试的效果

## 我如何完成这个项目

1. 上一下 javascript Testing [课程](https://www.udacity.com/course/ud549)
2. 下载[必要的项目资源]https://github.com/udacity/cn-frontend-development-advanced/raw/master/Feed%20Reader%20Testing_zh.zip
3. 在浏览器里面查看一下应用的功能
4. 查看项目的 HTMl (**./index.html**), CSS (**./css/style.css**) 和 JavaScript (**./js/app.js**) 文件来对项目的工作原理有一个基本的了解。
5. 查看 Jasmine spec 文件 **./jasmine/spec/feedreader.js** 然后翻阅阅读 [Jasmine 文档](http://jasmine.github.io)。
6. 编辑 **./js/app.js** 里面的 `allFeeds` 变量使给出的测试通不过，然后观察Jasmine是怎么展示你应用的错误信息的。
7. 将 `allFeeds` 变量复原
8. 编写一个测试遍历 allFeeds 对象里面的所有的源来保证有链接字段而且链接不是空的。
**检查对应字段的长度是否为0**
9. 编写一个测试遍历 allFeeds 对象里面的所有的源来保证有名字字段而且不是空的。
**检查对应字段的长度是否为0**
10. 写一个叫做 `"The menu"` 的测试用例
11. 写一个测试用例保证菜单元素默认是隐藏的。你需要分析 html 和 css 来搞清楚我们是怎么实现隐藏/展示菜单元素的。
**利用jQuery中hasClass()判断类名**
12. 写一个测试用例保证当菜单图标被点击的时候菜单会切换可见状态。这个测试应该包含两个 expectation ： 当点击图标的时候菜单是否显示，再次点击的时候是否隐藏。
**利用jQuery中trigger('click')模拟单击事件**
13. 写一个叫做 `"Initial Entries"` 的测试用例
14. 写一个测试保证 `loadFeed` 函数被调用而且工作正常，即在 `.feed` 容器元素里面至少有一个 `.entry` 的元素。
**利用jQuery中find()函数查找特定对象下的所有符合条件的子孙元素**
15. 写一个叫做 `"New Feed Selection"` 的测试用例
16. 写一个测试保证当用 `loadFeed` 函数加载一个新源的时候内容会真的改变。
**可通过检查两次加载结果中的内容进行判断(如第一项子元素的内容)**
**注意：jQuery对象的第一子元素可通过first()函数获得，所获得的对象也是jQuery对象**
**可使用回调函数进行嵌套，保证测试顺序和效果**
17. 每个测试都不应该依赖别的测试的结果。
18. 回调函数应该用来保证在测试运行之前源已经被加载。
19. 当完成所有任务的时候，所有的测试也应该通过。
20. 写一个 README 文件来详细说明运行应用的步骤。如果你已经添加了额外的测试（来提高测试覆盖率），请提供文档说明这些未来的功能点是什么和你编写的测试在检查什么。
