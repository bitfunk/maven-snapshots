# Bitfunk Maven Repository - Snapshots

Maven repository for snapshots of Bitfunk projects.

## Usage

NOTICE: Dependencies will be updated and cleaned regularly. So don’t include them in any production release.

### Gradle

Add following to your root `build.gradle` or `build.gradle.kts`

```Kotlin
repositories {
    maven("https://raw.github.com/bitfunk/maven-snapshots/main/repository")
}
```