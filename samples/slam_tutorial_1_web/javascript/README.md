#JavaScript version of slam_tutorial_1

## Bootstrap

### From NPM (Not Ready)
```
$ npm install
```

### From Source
Git clone the node-realsense repo:
```
$ git clone https://github.com/01org/node-realsense.git
```

Install the SLAM API moudle:
```
$ tar -C /path/to/node-realsense/src/ -hzcvf slam.tar.gz slam && npm install ./slam.tar.gz && rm slam.tar.gz
```

Install other dependencies:
```
$ npm install
```

## Run

```
$ node main.js
```
