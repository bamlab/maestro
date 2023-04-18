# Maestro fork for AWS CLI 🎹

## Run

```shell
./gradlew run --args="test ./test.yaml"
```

## Release

```shell
# Build
./gradlew distZip && unzip -o maestro-cli/build/distributions/maestro.zip -d dist
# Publish
cd dist/maestro
npm publish --tag rc
```
