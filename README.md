# QuPath-builds

QuPath is built with the following script:
```zsh
git clone git@github.com:qupath/qupath.git --depth 1
cd qupath/
jenv local openjdk64-14.0.1
./gradlew clean build createPackage
```

## v0.2.0-m12
built with:
- macOS 10.15.5 Beta (19F72f)
- openjdk64-14.0.1
