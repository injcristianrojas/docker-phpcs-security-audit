# PHPCS Security Audit for Docker

## Description

This project aims to make security analysis for PHP applications easier by
embedding the [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)
tool and its [PHPCS Security Audit](https://github.com/FloeDesignTechnologies/phpcs-security-audit)
module into a Docker machine.

The Docker project for this is located at
https://registry.hub.docker.com/u/injcristianrojas/phpcs-security-audit/

## Usage

Go to your PHP project directory and run:

```Shell
docker run --rm -it -v ${PWD}:/workdir:ro injcristianrojas/phpcs-security-audit
```
