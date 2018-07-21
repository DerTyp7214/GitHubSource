# GitHubSource

[![](https://jitpack.io/v/DerTyp7214/GitHubSource.svg)](https://jitpack.io/#DerTyp7214/GitHubSource)

[Latest Release](https://github.com/DerTyp7214/GitHubSource/releases/latest)

```gradle
implementation 'com.github.DerTyp7214:GitHubSource:3.2'
```

usage

```java
new Thread(() -> {
        GitHubSource.getInstance(
                Activity,
                new Repository(User, Repo, API_KEY)
        ).setColorStyle(new ColorStyle(
                PrimaryColor,
                PrimaryDarkColor,
                AccentColor
        )).open();
}).start();
```
