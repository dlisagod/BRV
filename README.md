<p align="center"><img src="https://i.imgur.com/S0IjjHS.jpg" alt="1600" width="25%"/></p>

<p align="center">
    <strong>可能是最强大的RecyclerView框架</strong>
    <br>
    <br>
    <a href="http://liangjingkanji.github.io/BRV/">使用文档</a>
    | <a href="https://github.com/liangjingkanji/document/blob/master/visit-pages.md">无法访问?</a>
    | <a href="https://liangjingkanji.github.io/document/">贡献代码</a>
    | <a href="https://github.com/liangjingkanji/BRV/releases/latest/download/brv-sample.apk">下载体验</a>
    <br>
    <img src="https://i.imgur.com/G7WYYXb.jpg" width="350"/>
</p>



<br>

<p align="center">
<a href="https://jitpack.io/#liangjingkanji/BRV"><img src="https://jitpack.io/v/liangjingkanji/BRV.svg"/></a>
<img src="https://img.shields.io/badge/language-kotlin-orange.svg"/>
<img src="https://img.shields.io/badge/license-Apache-blue"/>
<a href="http://liangjingkanji.github.io/BRV/updates"><img src="https://img.shields.io/badge/changed-%E6%9B%B4%E6%96%B0%E6%97%A5%E5%BF%97-brightgreen"/></a>
<a href="http://liangjingkanji.github.io/BRV/api"><img src="https://img.shields.io/badge/api-%E5%87%BD%E6%95%B0%E6%96%87%E6%A1%A3-red"/></a>
<img src="https://raw.githubusercontent.com/liangjingkanji/liangjingkanji/master/img/group.svg"/>
<a href="https://github.com/liangjingkanji/BRV/blob/master/docs/issues.md"><img src="https://raw.githubusercontent.com/liangjingkanji/Net/master/docs/img/issues.svg"/></a>
</p>


<p align="center"><img src="https://github.com/liangjingkanji/BRV/blob/master/docs/image/preview.png?raw=true" align="center" width="30%;" /></p>

本框架在不影响RecyclerView的任何函数组件使用基础上开发. 本项目承诺会永远保持社区维护

欢迎将本项目文档/注释进行国际化翻译, 感谢您的支持! <br>
Welcome to international translation of this project's documents/notes, thank you for your support!

<br>
<p align="center"><strong>欢迎贡献代码/问题</strong></p>
<br>

- [x] 开发效率No.1
- [x] 永远保持社区维护
- [x] 低代码/高扩展性
- [x] 优秀的源码/注释/文档/示例

<br>

## 功能

- [x] 快速创建多类型列表
- [x] 一对一/一对多创建多类型
- [x] 添加头布局和脚布局
- [x] 点击(防抖动)/长按事件
- [x] 分组(展开折叠/递归层次/展开置顶/拖拽/侧滑/多类型/单一展开模式)
- [x] 悬停/粘性头部
- [x] 快速创建分割线/间隔
- [x] 切换模式(例如切换编辑模式)
- [x] 选择模式(多选/单选/全选/取消全选/反选)
- [x] 拖拽排序
- [x] 侧滑删除
- [x] 下拉刷新(Refresh) | 上拉加载(LoadMore) | 下拉加载(UpFetch), 由[SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)实现
- [x] 预加载(Preload)
- [x] 对比数据更新(Diffs)
- [x] 自动分页加载数据
- [x] 列表动画/骨骼图动画
- [x] 列表缺省页, 由[StateLayout](https://github.com/liangjingkanji/StateLayout)实现
- [x] 支持DataBinding
- [x] 支持ViewBinding
- [x] 可添加[FlexboxLayoutManager](https://github.com/google/flexbox-layout)实现伸缩列表自动换行
- [x] 可添加[Net](https://github.com/liangjingkanji/Net)(强大的协程网络请求)实现自动化网络请求


## 安装

添加远程仓库根据创建项目的 Android Studio 版本有所不同

Android Studio Arctic Fox以下创建的项目 在项目根目录的 build.gradle 添加仓库

```groovy
allprojects {
    repositories {
        // ...
        maven { url 'https://jitpack.io' }
    }
}
```

Android Studio Arctic Fox以上创建的项目 在项目根目录的 settings.gradle 添加仓库

```kotlin
dependencyResolutionManagement {
    repositories {
        // ...
        maven { url 'https://jitpack.io' }
    }
}
```

然后在 module 的 build.gradle 添加依赖框架

```groovy
dependencies {
    //...
    implementation 'com.github.liangjingkanji:BRV:1.4.1'
}
```

项目根目录中 gradle.properties 添加

```
android.enableJetifier=true
android.useAndroidX=true
```

## License

```
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

