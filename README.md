# Spring-Boot-2.3demo

ref. https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-2.3-Release-Notes

ref. https://spring.io/blog/2020/05/15/spring-boot-2-3-0-available-now

## Build
./gradlew build

## Local SpringBootApp Run
./gradlew bootRun

## for AWS CodeBuild
SpringBootDemoApp → CodeBuild → ECR

ref. buildspec.yaml

## Access
https://(FQDN):8080/hello

`hello world!`

## Optional 
### Create Docker Image with Cloud Native Buildpacks
./gradlew bootBuildImage

### Code Formatter
./gradlew spotlessApply

### Environment
use spring boot actuator

see also. https://spring.pleiades.io/spring-boot/docs/current/reference/html/production-ready-features.html