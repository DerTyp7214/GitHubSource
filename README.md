# GitHubSource

```gradle
implementation 'com.github.DerTyp7214:GitHubSource:1.0'
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
