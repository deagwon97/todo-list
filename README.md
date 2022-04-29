# TODO List
TODO List example with Spring Boot, Kotlin and React.

## Prerequisites
- Docker 20.10.12
- docker compose 1.29.2
- VScode (for devcontainer)
  - Remote - Containers Extension(ms-vscode-remote.remote-containers)
  - Docker Extension(ms-azuretools.vscode-docker)

## Docker images version
- gradle:7-jdk11
- openjdk:11

## Start

### 1. Git Clone
```console
// clone source code
> git clone https://github.com/deagwon97/start-kotlin-spring-boot.git
```

### 2. Run Devcontainer
1. Open command palette
2. select "> remote-containers: open Folder in container.."
3. select "start-kotlin-spring-boot" directory

### 3. Development

If you want to run gradlew on CLI, to type this.

```console
# cd ~/workdir/src/
# ./gradlew bootRun
```

Or, if you want to use gradle extention debugger, do this.
1. click GADLE plugin on left side bar.
2. click Tasks > application > bootRun

but, you have to do run console `./gradlew bootRun` first once.


## Build

```
docker run build .
```