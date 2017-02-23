#JavaScript version of pt_tutorial_2_web

## Bootstrap

### From NPM (Not Ready)
```
npm install
```

### From Source
Git clone the node-realsense repo:
```
$ git clone https://github.com/01org/node-realsense.git
```

Install the person-tracking API moudle:
```
$ tar -C /path/to/node-realsense/src/ -hzcvf pt.tar.gz person-tracking && npm install ./pt.tar.gz && rm pt.tar.gz
```

Install other dependencies:
```
$ npm install
```

## Run

```
$ node main.js
```

Note: Open a brower in any remote machine that is on the same network as target, enter url "TargetIPaddr:8000/view.html". Ex:10.30.90.130:8000/view.html

