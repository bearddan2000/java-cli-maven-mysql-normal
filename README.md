# java-cli-maven-mysql-normal

## Description
Creates a small database table
called `dog`. This table, `dog`, has been normalized to 3NF.
Two new tables have been added, `breedLookup` and `colorLookup`.
All output normally
seen in a terminal will be in `java-srv/log` which will dump to the screen. The project may seem to hang but the logs from the container must be written to the project this can take up to 3 min.

## Tech stack
- java
- maven
  - log4j
  - mysql driver

## Docker stack
- maven:3-openjdk-17
- mariadb:latest

## To run
`sudo ./install.sh -u`
Creates java-srv/log

## To stop
`sudo ./install.sh -d`
Removes java-srv/log

## For help
`sudo ./install.sh -h`

## Credit
https://github.com/htorun/dbtableprinter

## java-cli specific search
- [Search by maven](https://github.com/bearddan2000?tab=repositories&q=java-cli-maven&type=&language=&sort=)
- [Search by mysql](https://github.com/bearddan2000?tab=repositories&q=java-cli-mysql&type=&language=&sort=)
- [Search by normal](https://github.com/bearddan2000?tab=repositories&q=java-cli-normal&type=&language=&sort=)
- [Search by log4j](https://github.com/bearddan2000?tab=repositories&q=java-cli-log4j&type=&language=&sort=)
- [Search by driver](https://github.com/bearddan2000?tab=repositories&q=java-cli-driver&type=&language=&sort=)

## General search
- [Search by java](https://github.com/bearddan2000?tab=repositories&q=java&type=&language=&sort=)
- [Search by cli](https://github.com/bearddan2000?tab=repositories&q=cli&type=&language=&sort=)
- [Search by maven](https://github.com/bearddan2000?tab=repositories&q=gradle&type=&language=&sort=)
- [Search by mysql](https://github.com/bearddan2000?tab=repositories&q=mysql&type=&language=&sort=)
- [Search by normal](https://github.com/bearddan2000?tab=repositories&q=normal&type=&language=&sort=)
- [Search by log4j](https://github.com/bearddan2000?tab=repositories&q=log4j&type=&language=&sort=)
- [Search by driver](https://github.com/bearddan2000?tab=repositories&q=driver&type=&language=&sort=)
