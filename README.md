# unicorn_li Android Unicorn SDK

## Gradle 集成

在项目的 `repositories` 中添加 GitHub Maven 仓库：

```gradle
repositories {
    maven {
        url 'https://qiyukf.github.io/QY_Android_SDK_Package/'
    }
}
```

在模块的 `dependencies` 中添加 SDK：

```gradle
dependencies {
    implementation 'com.qiyukf.unicorn:unicorn_li:x.x.xx'
}
```

将 `x.x.xx` 替换为需要使用的 SDK 版本号。
