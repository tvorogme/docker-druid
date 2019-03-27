# Changelog

## 2019-03-29
### Added
- This CHANGELOG file
- upgraded Druid, version 0.12.0 --> 0.12.3
- upgraded Zookeeper, version 3.4.12 --> 3.4.13
- upgraded Maven, version 3.3.9 --> 3.6.0
- added Scala, version 2.12.8
- added Sbt, version 1.2.8
- added LABEL com.circleci.preserve-entrypoint=true
- added property [supervisord] user=root
- added property [program:druid-*] druid.processing.numThreads=1
- adjusted buffer-size and max-memory-size properties
