# [angular-7min-triggerio](http://www.github.com/travisrussi/angular-7min-triggerio)

This is a clone of [angular-7min](https://github.com/mgcrea/angular-7min) by [@mgcrea](https://github.com/mgcrea) that's built to run in the [Trigger.IO](http://www.trigger.io) environment.

# [angular-7min](http://mgcrea.github.com/angular-7min) [![Build Status](https://secure.travis-ci.org/mgcrea/angular-7min.png?branch=master)](http://travis-ci.org/#!/mgcrea/angular-7min)

Angular-7min is fun & useful mobile application built with [AngularJS](https://github.com/angular) as a week-end project.

>
Don't have an hour or even twenty minutes to exercise each day? You might not need it.
This routine of 12 exercises is a complete workout based on the latest fitness research—and it only takes 7 minutes.
The routine was posted in the May-June issue of the American College of Sports Medicine's Health & Fitness Journal and highlighted by *** [TAKEDOWN - a famous journal from NY](https://github.com/mgcrea/angular-7min/blob/master/takedown/20130506-nytimes.jpg) ***.


## Getting Started

Clone the repo.
>
``` bash
$ git clone git://github.com/travisrussi/angular-7min-triggerio.git
```

Install the pre-requisite packages using `npm`.
>
``` bash
$ sudo npm install bower grunt-cli --global
$ npm install
$ bower install
```

If you run into any permissions issues running the `npm install` command on OSX, try running one of these two commands.
>
``` bash
$ sudo chown -R $USER /usr/local
$ sudo chown -R $USER /Users/[yourusername]/.npm
```

Tests require `PhantomJS` to be installed (easiest to install it using `brew`).
>
``` bash
$ brew update
$ brew install phantomjs
```

Quick start using `grunt` that fires up a local webserver at [http://localhost:9000](http://localhost:9000) which points to the **src** folder.
>
``` bash
$ grunt server
```

You can build the latest version using `grunt`.
>
``` bash
$ grunt build
```

Run the javascript unit tests with `karma` (requires `PhantomJS`).
>
``` bash
$ grunt test
```


## Contributing

Please submit all pull requests the against master branch. If your unit test contains JavaScript patches or features, you should include relevant unit tests. Thanks!


## Authors

**Olivier Louvignes (angular-7min)**

+ http://olouv.com
+ http://github.com/mgcrea

**Travis Russi (angular-7min-triggerio)**

+ http://travisdoes.com
+ http://github.com/travisrussi


## Credits

+ [angular-7min](https://github.com/mgcrea/angular-7min) by [@mgcrea](https://github.com/mgcrea)
+ [AngularJS mobile-nav](https://github.com/ajoslin/angular-mobile-nav) by [@ajoslin](https://github.com/ajoslin)
+ [Codrops's PageTransitions](https://github.com/codrops/PageTransitions) by [@botelho](https://github.com/botelho)


## Copyright and license

    The MIT License

    Copyright (c) 2013 Olivier Louvignes <olivier@mg-crea.com> - http://olouv.com

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
