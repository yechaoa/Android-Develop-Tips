# Android-Develop-Tips
### /storage/emulated/0/...
* 手机内部存储路径

### mEditText.setKeyListener(null); 
* EditText设置不可编辑，比focusable、enable更粗暴

### android:foreground="?android:attr/selectableItemBackground"
* item的水波纹效果，在item的View加上这一属性， 5.0+才行

### includeFontPadding="false"
* 去除TextView上下的padding

### viewpager的item点击事件
* viewpager底层拦截了点击事件，所以点击事件写在adapter里面

### android:imeOptions="actionDone"
* EditText修改软键盘的回车键

### android:contentDescription="@null"
* ImageView去除缺少描述的警告

### tools:text="预览"
* 使用tools属性工具预览布局 

### android:largeHeap="true"
*  给App增加更大的内存，AndroidManifest的Application 节点

### TextUtils.isEmpty() 
* 自带判空util

### TextView.setError() 
* 验证用户输入

### Context.getCacheDir()
* 获取缓存数据文件夹的路径

### DateUtils.formatDateTime() 
* 用来进行区域格式化工作，输出格式化和本地化的时间或者日期

### Linkify.addLinks() 
* 在Text上添加链接。很实用

### Fragment.setArguments
* 在创建 Fragment 之前设置参数

### LocalBroadcastManager
* 这个会比全局的 broadcast 更加安全，简单，快速

### PhoneNumberUtils.formatNumber ()
* 顾名思义，这是对数字进行格式化操作的时候用的

### Application.registerActivityLifecycleCallbacks
* 管理Activity的生命周期

### Activity.recreate ()
* 强制让 Activity 重建

### SparseArray
* Map的高效优化版本

### isShown()
* 判断view是否显示

### performClick()
* 模拟点击

### TextWatcher
* 监听EditText输入

### android:screenOrientation="portrait"
* activity 竖屏

### android:windowSoftInputMode="adjustPan|stateVisible"
* 适配带有输入框的页面

### android:weightSum="3"
* 设置LinearLayout中的权重总数

### android:fillViewport="true"
* ScrollView设置全屏

### SystemClock.sleep()
* 延时操作

### CountDownTimer
* 倒计时

### view.post()、View.postDelay()
* 更新UI，延时操作

### DateUtils.getRelativeTimeSpanString(long startTime)
* 返回 "几天前"/"xx days ago" 格式的字符串，自带翻译

### mWebView.canGoBack()
*  webview判断是否可返回

### DiffUtil
* 处理Recyclerview数据流

### setBackground(ContextCompat.getDrawable(this, R.drawable.icon))
* 代替setBackgroundDrawable()

### ContextCompat.getDrawable(context, R.drawable.your_drawable)
* 代替getDrawable(int)

### ContextCompat.getColor(context, R.color.color_name)
* 代替getColor(int)

### app:tabTextAppearance="@android:style/TextAppearance.Widget.TabWidget"
* 解决TabLayout默认英文大写

### android:textAllCaps="false"
* 解决Button默认英文大写

### android:includeFontPadding="false"
* 去掉TextView内部padding


### [快捷键](https://blog.csdn.net/yechaoa/article/details/53745386)
* 提高开发效率

### [live template动态模板](https://blog.csdn.net/yechaoa/article/details/77892495)
* 提高开发效率

### [Android快速开发整理（库、插件、常用网站）](https://github.com/yechaoa/Android-Rapid-Development)
* 提高开发效率

<br>

#### [Github Android-Develop-Tips](https://github.com/yechaoa/Android-Develop-Tips)

欢迎补充

<br>

```
   License

   Copyright 2018 yechaoa

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

