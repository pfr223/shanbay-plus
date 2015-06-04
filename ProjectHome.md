为扇贝网（www.shanbay.com）增加一些易用小功能，包括：查词界面增加美式发音,删除单词;批量添加单词增强;单词书创建增强;查词限制;

---------------------------------下载说明----------------

谷歌已经停用下载支持，下载请去[我的网盘](http://pan.baidu.com/s/1ntykrI5)

用火狐的去[这里](http://userscripts.org/scripts/show/352241)

---------------------------------安装说明----------------

Chrome does not allow scripts to be installed directly from the website, so here are a couple of workarounds:

Manual Install

  1. Click the install button to download the script to your computer.
  1. Click on the "Customize Google Chrome Button" to the right of the address bar and go to Tools > Extensions.
> > (Or access chrome://extensions/ directly)
  1. Drag the downloaded script onto the Extensions page
> > <img src='http://geekpark-img.qiniudn.com/uploads/reading/seed/db65c0dbc951b90407b84530ffe68836.png' />
  1. Customize and install the script


---------------------------------更新历史---------------

Version 0.87

添加了来自vocabulary.com的例句

Version 0.86

增加超时控制，避免查询vocabulary.com时偶发的无限等待。

Version 0.84

1 美化了一下助记的界面，使得和扇贝风格一致。

> http://s3.amazonaws.com/uso_ss/25570/large.jpg?1393901133
2 修改了有可能干扰扇贝正常功能的地方，例如：不再在查词窗上加删除按钮了；查词限制功能现在仅提示查词数，不做真正的限制。

Version 0.83

扇贝改了查词窗口，插件的查词不能用了，只好跟着改

Version 0.82

同样是bugfix版本
> 助记信息的展开收起支持快捷键操作。
> 通过缓存到本地（indexedDB）来减少网络延迟的情况。

Version 0.81

这是一个bugfix版本
> 界面做了调整，默认放在最上面，但是可以自己在选项中定制位置。
> 默认是收起状态，避免过多版面占用
> 降低了网络延迟，背单词过程中会预加载

Version 0.8

单词详情页增加高大上的助记信息：用一段浅显的英文解释单词含义，并附有词根典故或扩展阅读

Version 0.7

新版背单词的跳过模式
（这个功能默认是关闭的，无法忍受新版一次次询问认不认识的同学，可以参照选项配置说明，将这个选项打开。开启跳过模式后，对于不认识的词，只要选一次不认识，就可立刻进入详情页，节省你的时间）

Version 0.6

解除批量添加单词时的数量限制
(易用性的改进：扇贝限制一次只能提交10个，超出了就不让提交。本插件一次仍然只提交10个，但是超出的部分保留在文本框内，方便你再次提交)

Version 0.5

单词书可批量加词
> http://s3.amazonaws.com/uso_ss/25250/large.jpg?1392112102

Version 0.4

阅读查词限制
（阅读时不是查的越多越好，具体理论可百度透析英语。本插件屏蔽了超出次数的查询。默认给了一个比较宽松的值：平均330个词可查一次，有需要的可自行调整，但是不建议调的更低，因为如果这个适应不了，你应该降低阅读材料的难度了）
> http://s3.amazonaws.com/uso_ss/25247/large.jpg?1392085741

Version 0.3

批量添加单词可显示掌握程度
（你批量添加时，如果你认为的生词其实你背过但是忘了，扇贝并没有告诉你。本插件将背过的词的掌握程度显示出来，并且你可以随时选择“我忘了”）
> http://s3.amazonaws.com/uso_ss/25245/large.jpg?1392011006

Version 0.2

1.查词窗口增加美式发音
2.查词窗口可直接删除单词
> http://s3.amazonaws.com/uso_ss/25219/large.png?1391866861