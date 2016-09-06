# AndroidStudioPlugins
Android Studio 常用插件及浅释

也可以看我的博客：[Android Studio中常用插件及浅释](http://t.cn/RGr9lIf)

插件可以来这个仓库查找：[Android Studio Plugins](http://plugins.jetbrains.com/category/?androidstudio&category_id=all)

这里给出几个平时常用的as插件，方便我们的开发。点击标题就直接可以进入插件的github源码查看。

如何自己开发插件，请参考鸿洋大神的博客：[自己编写Android Studio插件 别停留在用的程度了](https://mp.weixin.qq.com/s?__biz=MzAxMTI4MTkwNQ==&mid=2650820316&idx=1&sn=49d4e6b68b114a2e8a8e88f3d1b0cd9e&scene=1&srcid=0601lzX1UwNhWeitdRa3Bmfx#rd)

# [.ignore](https://github.com/hsz/idea-gitignore)
---

as第一大插件，版本控制必备，.gitignore内容写法，来这里看看：[git使用之二——.gitignore文件详解 ](http://jp1017.gitcafe.io/2015/12/20/git%E4%BD%BF%E7%94%A8%E4%B9%8B%E4%BA%8C%E2%80%94%E2%80%94-gitignore%E6%96%87%E4%BB%B6%E8%AF%A6%E8%A7%A3/)

# [SingletonTest](https://github.com/luhaoaimama1/SingletonTest)
---

快速生成单例模式的预设

<img src="https://raw.githubusercontent.com/luhaoaimama1/SingletonTest/master/demo/tip1.png" width="270"/> <img src="https://raw.githubusercontent.com/luhaoaimama1/SingletonTest/master/demo/tip2.png" width="270"/> <img src="https://raw.githubusercontent.com/luhaoaimama1/SingletonTest/master/demo/tip3.png" width="270"/>

# [img-optimizer-gradle-plugin](https://github.com/chenenyu/img-optimizer-gradle-plugin)
---

一款用于优化png图片的gradle插件，有效减少APK体积，支持极限压缩和无损压缩

|原图|极限压缩(lossy)|无损压缩(lossless)|
|:---:|:---:|:---:|
|526K|195K(减少63%)|473K(减少10%)|
|![原图](https://github.com/chenenyu/img-optimizer-gradle-plugin/blob/master/arts/lenna.png)|![极限压缩](https://github.com/chenenyu/img-optimizer-gradle-plugin/blob/master/arts/lenna_lossy.png)|![无损压缩](https://github.com/chenenyu/img-optimizer-gradle-plugin/blob/master/arts/lenna_lossless.png)|

# [drawable-optimizer](https://github.com/fabiomsr/drawable-optimizer)
---

### 功能：优化项目中的 `png` 文件

只要配置下 gradle 文件就可以：

1 在 root gradle 文件下添加

```
classpath 'org.fabiomsr:drawable-optimizer-gradle-plugin:1.0.4'
```

2 在 app 下 gradle 文件配置插件

```
apply plugin: 'org.fabiomsr.drawableoptimizer'


drawableOptimizer {
    optimizer = 'zopfli'
    compressionLevel = 9
    iterations = 15
    onlyOnRelease = true
    logLevel = 'info'
}
```

# [wakatime](https://github.com/wakatime/jetbrains-wakatime)
---

记录你AS使用时长的插件，当然还支持很多IDE。使用时需要登录配置key，来这里：https://wakatime.com/settings/account

<img src="https://camo.githubusercontent.com/0263e365a2efdb5dc0adb4b7aba6a783bc17a92e/68747470733a2f2f77616b6174696d652e636f6d2f7374617469632f696d672f53637265656e53686f74732f53637265656e2d53686f742d323031362d30332d32312e706e67" width="600"/>

# [Material Theme UI](https://github.com/ChrisRM/material-theme-jetbrains)
---

MD 风格主题，强烈建议添加，各种爱的不行不行的

<img src="https://camo.githubusercontent.com/5a9c869268720fa615ef6b7bf2efc14e9575ef4f/687474703a2f2f63646e2e6869666976652e6e6f2f6d6174657269616c2d75692f7468656d652d64656661756c742e706e67" width="600"/>

# [Sexy Editor](https://github.com/igorspasic/idea-sexyeditor)
---

设置 as 背景，赶紧上车了

<img src="https://raw.githubusercontent.com/igorspasic/idea-sexyeditor/master/sexyeditor.jpg" width="600"/>

# [Android DPI Calculator](https://github.com/JerzyPuchalski/Android-DPI-Calculator)
---

DPI 计算工具

<img src="https://camo.githubusercontent.com/ce3be2aaa3b1f70b90f5b825c529694509d70313/68747470733a2f2f7261772e6769746875622e636f6d2f4a65727a7950756368616c736b692f416e64726f69642d4450492d43616c63756c61746f722f6d61737465722f696d672f6469616c6f672e706e67" width="400"/> <img src="https://camo.githubusercontent.com/7a8f977de7a1ba6cd23fb64cbd37566690c27cdc/68747470733a2f2f7261772e6769746875622e636f6d2f4a65727a7950756368616c736b692f416e64726f69642d4450492d43616c63756c61746f722f6d61737465722f696d672f6d656e752e706e67" width="300"/>


# [RemoveButterKnife](https://github.com/u3shadow/RemoveButterKnife)
---

帮助去掉 ButterKnife 库的 android studio 插件

<img src="https://camo.githubusercontent.com/0327cda5b531ab6f2b803abe295c42225668d28d/687474703a2f2f7777772e7533636f64696e672e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031362f30362f312e676966" width="600"/>


# [ECTranslation](https://github.com/Skykai521/ECTranslation)
---

可以将英文翻译为中文

<img src="https://raw.githubusercontent.com/Skykai521/ECTranslation/master/img/translation_img.png" width="600"/>

# [eventbus3-intellij-plugin](https://github.com/likfe/eventbus3-intellij-plugin)
---

EventBus3 事件管理，最新可用

<img src="https://raw.githubusercontent.com/kgmyshin/eventbus3-intellij-plugin/master/art/cap.gif" width="600"/>

@deprecated
# <del>[eventbus3-intellij-plugin](https://github.com/kgmyshin/eventbus3-intellij-plugin)</del>
---

EventBus3 事件管理，已失效

<img src="https://raw.githubusercontent.com/kgmyshin/eventbus3-intellij-plugin/master/art/cap.gif" width="600"/>

# [eventbus-intellij-plugin](https://github.com/kgmyshin/eventbus-intellij-plugin)
---

EventBus 事件管理

<img src="https://raw.githubusercontent.com/kgmyshin/eventbus-intellij-plugin/master/art/cap.gif" width="600"/>

# [PermissionsDispatcher](https://github.com/shiraji/permissions-dispatcher-plugin)
---

IntelliJ plugin for supporting PermissionsDispatcher

<img src="https://raw.githubusercontent.com/shiraji/permissions-dispatcher-plugin/master/website/images/pd.gif" width="600"/>

# [Android Methods Count](http://www.methodscount.com/plugins)
---

展示安卓依赖库里方法数，支持的仓库包括：`Maven Central`, `jCenter`, `JitPack`

![1](http://www.methodscount.com/images/methods-count-plugin-1.png)
![2](http://www.methodscount.com/images/methods-count-plugin-2.png)

# [Genymotion](https://www.genymotion.com/#!/download)
---

速度快，运行流畅的安卓模拟器

来这里吧，专门给你准备的：[Eclipse和Android Studio下安装Genymotion模拟器插件](http://www.ebaina.com/bbs/forum.php?mod=viewthread&tid=8418&extra=page%3D1)

# [ButterKnife Zelezny](https://github.com/avast/android-butterknife-zelezny)
---

Android Studio plug-in for generating ButterKnife injections from selected layout XML.

插件下载如下：

![1](http://7xlah4.com1.z0.glb.clouddn.com/20150928202523.png)

要配合一个库com.jakewharton:butterknife:7.0.1使用，把该库添加到build.gradle脚本里即可。

![2](http://7xlah4.com1.z0.glb.clouddn.com/20150928194919.png)

使用如下：

比如我们在activity的布局里定义了一个文本框，三个按钮，共四个id，然后我们来注解一下：鼠标放setContentView(R.layout.activity_main);下的activity_main任意位置，alt+insert，然后注解：

![3](http://7xlah4.com1.z0.glb.clouddn.com/20150928194920.gif)

# [Android Studio Prettify](https://github.com/Haehnchen/idea-android-studio-plugin)
---

Android Studio plugin with some tools and usability improvements, Generator for inflater and activity setContentView view variables.

如果你布局里有多个id，在activity里findViewById()会手写很多次，即使有ide辅助，但是还是略慢，这个插件就来释放你双手，作者的例子：

![Prettify](http://7xlah4.com1.z0.glb.clouddn.com/2015101834.gif)

![Prettify2](http://7xlah4.com1.z0.glb.clouddn.com/2015101833.png)

当然如果快速注解的话就用上面的ButterKnife咯。

# [ADB WIFI](https://github.com/layerlre/ADBWIFI)
---

通过wifi调试你的安卓app，释放usb数据线，实现调试无处不在。。。

使用方法：
确保你的手机和电脑在同一wifi下，首先用usb连接手机很电脑，第一次还是需要的，后面连接完成后可以拔掉。然后连接他们， Tools → Android → ADB WIFI → ADB USB to WIFI 成功后会在右上角有个对话框，提示成功。然后拔掉你的数据线，调试无处不在模式开启。。。

![连接](http://7xlah4.com1.z0.glb.clouddn.com/201510211.jpg)

# [GsonFormat](https://github.com/zzz40500/GsonFormat)
---

根据JSONObject格式的字符串,自动生成实体类参数。
最新的1.2.0版本新增处女座模式 →_→ 是不是很贴心！

 处女座模式就是给json每个key都可以配置生成的filedName，可能因为服务端的原因，或者历史的原因，导致服务器返回的字段名诡异，或是歧义的缩写。这个在之前的版本是不支持这个。

作者给出的例子：

有如下json数据：

```xml
{
    "name": "王五",
    "gender": "man",
    "age": 15,
    "height": "140cm",
}
```

生成实体类操作如下，win和linux下的快捷键是alt+insert

![GsonFormat](http://7xlah4.com1.z0.glb.clouddn.com/2015101831.gif)

# [LeakCanary](https://github.com/square/leakcanary)
---

良心企业Square最近刚开源的一个非常有用的工具，使用方法请看我的另一片文章：[Android Studio 插件之内存泄露检测LeakCanary使用](http://jp1017.gitcafe.io/2015/12/20/Android-Studio-%E6%8F%92%E4%BB%B6%E4%B9%8B%E5%86%85%E5%AD%98%E6%B3%84%E9%9C%B2%E6%A3%80%E6%B5%8BLeakCanary%E4%BD%BF%E7%94%A8/)

# [codota](https://www.codota.com/)
---

该网站搜集了大量的代码，号称超过700W的代码实例。
它提供了chrome插件和as插件。

按照同样的方式安装codota插件之后，重启AS。使用快捷键ctrl + k，即可打开搜索界面，如果你的快捷键有冲突，随便打开一个界面，然后右键就可以看到Search Cotoda选项。

# [Android Code Generator](https://github.com/tmorcinek/android-codegenerator-plugin-intellij)
---

如果你的xml布局里有n个id，需要用findViewById找到的话，手动的话，很累，这个插件就是释放你的双手，轻轻一点，轻松生成代码，然后你复制粘贴到你的代码就ok，我们来看：

![Android Code Generator](http://7xlah4.com1.z0.glb.clouddn.com/2015101101.gif)

# [Android Postfix completion](https://github.com/takahirom/android-postfix-plugin)
---

该插件可以快速书写log、toast等代码

![log](http://7xlah4.com1.z0.glb.clouddn.com/20151011172328.png)

我们来具体操作：

![toast](http://7xlah4.com1.z0.glb.clouddn.com/2015101102.gif)

# [Android Selectors Generate](https://github.com/inmite/android-selector-chapek)
---

Android Studio plugin which automatically generates drawable selectors from appropriately named resources.

自动生成选择器，这玩意好用，很赞，但是要注意drawable下文件后缀哦，告诉美工小妹妹命名好哦，哈哈。

文件后缀是这样的：

![文件后缀](http://7xlah4.com1.z0.glb.clouddn.com/2015101850.png)

使用方法：

1 右击drawable文件夹：

![右击](http://7xlah4.com1.z0.glb.clouddn.com/2015101851.png)

2 选择Generate Android Selectors

![selectors](http://7xlah4.com1.z0.glb.clouddn.com/2015101852.png)

3 自动生成选择器

![选择器](http://7xlah4.com1.z0.glb.clouddn.com/2015101853.png)

# [Android File Grouping](https://github.com/dmytrodanylyk/folding-plugin)
---

去官网学习吧，用处不是很大，方便阅读。

# [FindBugs-IDEA](https://github.com/andrepdo/findbugs-idea/tree/master)
---

顾名思义，就是帮你找程序bug咯，自己研究去吧，给力，感恩作者。

# [Android Parcelable code generator](https://github.com/mcharmas/android-parcelable-intellij-plugin/)
---

安卓下，推荐用Parcelable来实现数据序列化，如果需要实现Serilizeable接口的，也有插件，[SerializableParcelableGenerator](https://github.com/bunnyblue/SerializableParcelableGenerator)

使用也很简单，进入要序列化的bean类里，windows，linux下直接快捷键alt+insert，mac下右键Generator, 可以看到有个选项Parcelable，然后直接点击，就序列化完成咯。

![Parcelable](http://7xlah4.com1.z0.glb.clouddn.com/20151230012.gif)

# [Android Drawable Importer](https://github.com/winterDroid/android-drawable-importer-intellij-plugin)
---

最常用的功能就是生成不同尺寸的图标，

我这里有个需求，美工妹妹要陪男朋友，然后只给我一套xxh的图标，那么这个工具就是来解放你们的，手把手的教：

![Drawable](https://raw.githubusercontent.com/winterDroid/android-drawable-importer-intellij-plugin/develop/src/main/resources/images/scale_add.png)

# [android-material-design-icon-generator-plugin](https://github.com/konifar/android-material-design-icon-generator-plugin)
---

This plugin help you to set material design icon to your project.

![material](https://raw.githubusercontent.com/konifar/android-material-design-icon-generator-plugin/master/docs/capture.gif)

# [AndroidStudioSuperPlugin](https://github.com/b2b2244424/AndroidStudioSuperPlugin)
---

这个是今天（2016年植树节）早上发现的，是几个插件的集成，包括：

+ Android Studio Prettify
+ GsonFormat
+ Android Code Generator
+ SelectorChapek
+ Android Parcelable Generator
+ folding-plugin
+ Lifecycle-Sorter

有了这个，可以删掉相关的插件咯，谢谢，哈哈哈

# [CodeGlance](https://github.com/Vektah/CodeGlance)
---

Intelij IDEA plugin for displaying a code mini-map similar to the one found in Sublime

![CodeGlance](http://7xlah4.com1.z0.glb.clouddn.com/20160317.png)

# [lint-cleaner-plugin](https://github.com/marcoRS/lint-cleaner-plugin)
---

### 功能：清除项目中的无用资源

只要配置下 gradle 文件就可以：

1 在 root gradle 文件下添加

```
classpath 'com.droidtitan:lint-cleaner-plugin:0.3.0'
```

2 在 app 下 gradle 文件配置插件

```
apply plugin: 'com.droidtitan.lintcleaner'


lintCleaner {
    // Exclude specific files
    exclude = ['com_crashlytics_export_strings.xml','config.xml']

    // Ability to ignore all resource files. False by default. 
    ignoreResFiles = true

    // Default path is build/outputs/lint-results.xml
    lintXmlFilePath = 'path/to/lint-results.xml'
}
```


最后，非常感谢您的阅读，有任何疑问，可以后面评论，我们可以互相探讨，共同进步，谢谢！

神奇的安卓开发网站：[http://androidcat.com/](http://androidcat.com/)

安卓开源库收集整理：[https://github.com/XXApple/AndroidLibs](https://github.com/XXApple/AndroidLibs)

分享是一种美德，更是一种生活方式！！

>也许你会说我是一个梦想者，但我不是唯一的一个。

>悦分享，越快乐^_^

欢迎交流，转载请注明出处，谢谢！
