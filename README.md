# renovate-maven-extensions

In order to reproduce and test maven extensions with Renovate

At the time of writting the extension should be bumped to `1.7` at least.

If you add the dependency on the pom

```
<dependencies>
    <dependency>
        <groupId>io.jenkins.tools.incrementals</groupId>
        <artifactId>git-changelist-maven-extension</artifactId>
        <version>1.6</version>
    </dependency>
</dependencies>
```

Renovate is able to to bump it. But not as a maven extension 😞