# Download
You can find the latest version of Coffeecord [here](https://github.com/Coffeecord/Coffeecord/releases).

# Adding to your project
!!! note "Version"
    Replace `VERSION` in your build file with the version of Coffeecord you'd like to use.

!!! note "Case-sensitive"
    Dependency information in almost all build tools is case-sensitive, so make sure you use the proper casing!

=== "Gradle"
    ```gradle linenums="1"
    dependencies {
        implementation("xyz.deftu.coffeecord:Coffeecord:VERSION")
    }
    ```

=== "Maven"
    ```maven linenums="1"
    <dependencies>
        <dependency>
            <groupId>xyz.deftu.coffeecord</groupId>
            <artifactId>Coffeecord</artifactId>
            <version>VERSION</version>
        </dependency>
    </dependencies>
    ```

=== "SBT"
    ```sbt linenums="1"
    libraryDependencies += "xyz.deftu.coffeecord" % "Coffeecord" % "VERSION"
    ```

=== "Leiningen"
    ```leiningen linenums="1"
    :dependencies [[xyz.deftu.coffeecord/Coffeecord "VERSION"]]
    ```