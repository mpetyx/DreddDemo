# DreddDockerDemo
A Quick Demo to get Dredd API testing in Docker.

This demo will build a docker container for [Dredd](https://dredd.readthedocs.io/en/latest/)
API testing with a simple [Go](https://golang.org/)
web application and utilizing [Node.js](https://dredd.readthedocs.io/en/latest/hooks-nodejs/) hooks for Dredd.

To run test
```
make dreddtest
```

Requires
- Docker

Travis CI [![Build Status](https://travis-ci.org/jasonrichardsmith/DreddDockerDemo.svg?branch=master)](https://travis-ci.org/jasonrichardsmith/DreddDockerDemo)

Circle CI [![CircleCI](https://circleci.com/gh/jasonrichardsmith/DreddDockerDemo.svg?style=svg)](https://circleci.com/gh/jasonrichardsmith/DreddDockerDemo)

Snap CI [![Build Status](https://snap-ci.com/jasonrichardsmith/DreddDockerDemo/branch/master/build_image)](https://snap-ci.com/jasonrichardsmith/DreddDockerDemo/branch/master)
