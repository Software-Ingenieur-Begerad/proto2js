# proto2js
Compile *.proto file to JavaScript module

## Table of Contents
0. [General](#General)
1. [GTFS Realtime](#gtfs-realtime)

# General
This repository provides three folders for each compilation
1. ```doc```: Documentation
2. ```proto```: Source file
3. ```js```: Result file

The tools used for compilation is called
[pbf](https://github.com/mapbox/pbf)
and installed in a global fashion like this.
```
$ npm install -g pbf
```

A compilation is done by calling the following instructions.
```
pbf ./proto/<file.proto> > ./js/<file.js>
```

# [GTFS Realtime](./doc/gtfs-rt)
