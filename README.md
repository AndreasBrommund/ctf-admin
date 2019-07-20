# CTF-admin

[![Build Status](https://travis-ci.org/AndreasBrommund/ctf-admin.svg?branch=master)](https://travis-ci.org/AndreasBrommund/ctf-admin)

## Java
Java 11.0

## Guide
* https://spring.io/guides/gs/rest-service/
* https://guides.gradle.org/executing-gradle-builds-on-travisci/
* https://github.com/dwyl/learn-travis/blob/master/encrypted-ssh-keys-deployment.md
* https://blog.travis-ci.com/2019-05-30-setting-up-a-ci-cd-process-on-github

## Run 
### Option 1
1. ./gradlew build
2. java -jar build/libs/ctf-admin-0.1.0.jar 

### Option 2
1. ./gradlew bootRun

## Branches
* test-server: auto deployed to the [test server](http://brommund.dskeppstedt.se:50000)
* master: auto deployed to the  [prod server](http://brommund.dskeppstedt.se:50001)
