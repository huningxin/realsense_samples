#JavaScript version of or_tutorial_2_web

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

Install the object-recognition API moudle:
```
$ tar -C /path/to/node-realsense/src/ -hzcvf or.tar.gz object-recognition && npm install ./or.tar.gz && rm or.tar.gz
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

