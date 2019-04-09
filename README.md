# Maven Repository for Jason

Using gradle:

```
repositories {
   mavenCentral()
   jcenter()
   google()

   maven { url "https://raw.github.com/rosjava/rosjava_mvn_repo/master" }

   maven { url "https://raw.github.com/jason-lang/mvn-repo/master" }
   maven { url "http://jacamo.sourceforge.net/maven2" }
}

dependencies {
   compile group: 'org.jason-lang',     name: 'jasonros' ,   version: '1.0'
}
```
