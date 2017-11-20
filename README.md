# Gradle
## Step 1 - Discover the CLI

```bash
gradle -h
gradle --status
gradle tasks
gradle help --task tasks
gradle help --task init
``` 

## Step 2 - Create first project

```bash
gradle init
```
* build.gradle
* settings.gradle
* gradle/
* gradlew

## Step 3 - Bootstrap

New tasks added
```bash
gradle init --type java-library
gradle tasks
```

## Step 4 - Bootstrap

New tasks added
```bash
gradle init --type java-aplication
gradle tasks
```

## Step 5 - Incremental build

Run the build twice 
```bash
gradle build
gradle build
```

## Step 6 - Enhanced dependency management

```bash
gradle dependecies
gradle dependencies --configuration testCompile
gradle properties
gradle -m build
gradle -m test
```

- old compile became implementation, for maven it is equivalent of runtime
- api is compile for maven 

## Step 7 : Improve your build 

```bash
gradle build --profile
gradle build --scan
gradle build --scan --parallel
gradle build --scan --parallel --build-cache compileJava
```
Cache can be distributed among the company

## Step 8 : Composite build

```bash
gradle run --include-build=../algorithms
```

## Step 9 : RT(F)M :)
There is a lot more !

## Links
```bash
hg clone https://bitbucket.org/NargiT00/algorithms
git clone https://github.com/NargiT/sq-gradle
```
