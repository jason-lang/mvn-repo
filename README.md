# Maven Repository for Jason

Using gradle:

```
repositories {
   mavenCentral()
   jcenter()
   
   maven { url "https://raw.github.com/rosjava/rosjava_mvn_repo/master" }
   maven { url "https://raw.github.com/jason-lang/mvn-repo/master" }
   maven { url "http://jacamo.sourceforge.net/maven2" }
}

dependencies {
   compile group: 'org.jason-lang',     name: 'jason' ,   version: '2.4-SNAPSHOT'
   compile group: 'org.jason-lang',     name: 'jasonros' ,   version: '1.0'
   compile group: 'org.jason-lang',     name: 'jasonros_msgs' ,   version: '1.0'
}
```
