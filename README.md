<img src="http://img.jcabi.com/logo.png" width="200px" height="48px" />

More details are here: [www.jcabi.com/jcabi-manifests](http://www.jcabi.com/jcabi-manifests/index.html)

Manipulations with MANIFEST.MF files made easy:

```java
import com.jcabi.manifests.Manifests;
public class Main {
  public static void main(String[] args) {
    String version = Manifests.read("JCabi-Version");
    System.out.println("version is " + version);
  }
}
```

You need just this dependency:

```xml
<dependency>
  <groupId>com.jcabi</groupId>
  <artifactId>jcabi-manifests</artifactId>
  <version>1.0</version>
</dependency>
```

## Questions?

If you have any questions about the framework, or something doesn't work as expected,
please [submit an issue here](https://github.com/yegor256/jcabi/issues/new).
If you want to discuss, please use our [Google Group](https://groups.google.com/forum/#!forum/jcabi).

## How to contribute?

Fork the repository, make changes, submit a pull request.
We promise to review your changes same day and apply to
the `master` branch, if they look correct.

Please run Maven build before submitting a pull request:

```
$ mvn clean install -Pqulice
```
