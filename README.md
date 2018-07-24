# GitHubSource

[Latest Release](https://github.com/DerTyp7214/GitHubSource/releases/latest)

```gradle
implementation(name: 'GitHubSource', ext: 'aar')
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
