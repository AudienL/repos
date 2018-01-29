# repos

> 这是一个仓库，专门存放我自己写的一些框架和工具什么的，并没有实质的代码。
> 如果你也想拥有一个，请[参考博客](http://www.jianshu.com/p/ca53952f4212)

## 使用

```
allprojects {
    repositories {
        maven { url "https://raw.githubusercontent.com/AudienL/repos/master" }
    }
}

compile 'xxx:xxx:xxx'
```


## 所有项目

### SuperLibrary

```
compile 'com.audienl:super_library:1.2.1'

// 如果需要排除依赖
compile('com.audienl:super_library:1.2.1', {
    exclude group: 'com.android.support', module: 'support-v4'
    exclude group: 'com.android.support', module: 'appcompat-v7'
    exclude group: 'com.android.support', module: 'recyclerview-v7'
    exclude group: 'com.android.support', module: 'animated-vector-drawble'
    exclude group: 'com.android.support', module: 'support-compat'
    exclude group: 'com.android.support', module: 'support-annotations'
    exclude group: 'com.android.support', module: 'support-fragment'
    exclude group: 'com.android.support', module: 'support-vector-drawable'
    exclude group: 'com.android.support', module: 'support-media-compat'
    exclude group: 'com.android.support', module: 'support-core-ui'
    exclude group: 'com.android.support', module: 'support-core-utils'
})
```

[源代码：https://github.com/AudienL/SuperLibrary](https://github.com/AudienL/SuperLibrary)
