### II.	Dependencies
The principle never relies on the implicit existence of system-wide packages. It declares all dependencies, completely and exactly, via a dependency declaration manifest. Furthermore, it uses a dependency isolation tool during execution to ensure that no implicit dependencies "leak in" from the surrounding system.
e.g., from Java perspective, Maven and Gradle are the examples of dependency manager which allows users to specify the dependencies and also to exclude the implicit dependencies which should not be the part of the system.

Let's take an example of Maven. Maven requires to describe a project's dependencies in an XML file, typically known as Project Object Model (POM). Below is one sample of including dependencies in the POM file and excluding one of the transitive dependencies -

```sh
<dependency>
  <groupId>com.example</groupId>
  <artifactId>foo-bar</artifactId>
  <version>1.2.3</version>
   <exclusions>
     <exclusion>
        <groupId>org.slf4j</groupId>
        <artifactId>slf4j-api</artifactId>
     </exclusion>
   </exclusions>
</dependency>
```

