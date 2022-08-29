# scala-cli-bloop-sbt-ugly-number-pattern-match

## Description
Divide the number by greatest divisible powers of
2, 3 and 5, if the number becomes 1 then it is an
ugly number otherwise not.
Follows functional programming practices. Example of pattern matching.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- openjdk 8
- scala
- bloop-sbt

## Docker stack
- docker-cli
- openjdk:8

## Requirements
Docker desktop must be installed and the application
being called must be linux compatiple.

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## To see help
`sudo ./install.sh -h`
