## CloudMonkey [![Build Status](https://travis-ci.org/apache/cloudstack-cloudmonkey.svg?branch=master)](https://travis-ci.org/apache/cloudstack-cloudmonkey)

`cloudmonkey` :cloud::monkey_face: is a command line interface (CLI) for
[Apache CloudStack](http://cloudstack.apache.org).
CloudMonkey can be use both as an interactive shell and as a command line tool
which simplifies Apache CloudStack configuration and management.

The modern cloudmonkey is a re-written and simplified port in Go and can be used
with Apache CloudStack 4.9 and above. The legacy cloudmonkey written in Python
can be used with Apache CloudStack 4.0-incubating and above.

### Usage

Work in progress: 6.0.0-alpha1 (TO BE UPDATED soon)

For modern cloudmonkey usage, please see the [usage page](https://github.com/apache/cloudstack-cloudmonkey/wiki/Usage).

Legacy cloudmonkey can be installed using `pip install cloudmonkey`.
For legacy cloudmonkey, please see the [cwiki usage page](https://cwiki.apache.org/confluence/display/CLOUDSTACK/CloudStack+cloudmonkey+CLI).

### Development

The following are various make targets you can run:

    $ make help

      all               Build program binary
      run               Builds and runs cloudmonkey
      dist              Builds release for various targets
      clean             Cleans build artifacts
      lint              Run golint
      fmt               Run gofmt on all source files
      check test tests  Run tests
      test-bench        Run benchmarks
      test-short        Run only short tests
      test-verbose      Run tests in verbose mode with coverage reporting
      test-race         Run tests with race detector
      test-xml          Run tests with xUnit output
      test-coverage     Run coverage tests

Build and run:

    $ make run

Build and run manually:

    $ make all
    $ ./bin/cloudmonkey

### Community

You may join the relevant mailing list(s) for cloudmonkey related discussion:

[Development Mailing List](mailto:dev-subscribe@cloudstack.apache.org)

[Users Mailing List](mailto:users-subscribe@cloudstack.apache.org)

### Contribution

Discuss issue(s) and feature(s) on CloudStack [development mailing list](mailto:dev-subscribe@cloudstack.apache.org).
Report issue(s) on the `user` mailing list and/or open a Github [issue](https://github.com/apache/cloudstack-cloudmonkey/issues).

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Commit your change
4. Write tests for your change if applicable
5. Run the tests, ensuring they all pass
6. Submit a [Pull Request](https://github.com/apache/cloudstack-cloudmonkey/pull/new/master) using Github

### History

`cloudmonkey` was originally written in Python and contributed to Apache CloudStack
project by [Rohit Yadav](http://rohityadav.cloud) on 31 Oct 2012 under the Apache
License 2.0. The original tool is also referred to as legacy cloudmonkey can
be installed using `pip install cloudmonkey`.

Starting version 6.0.0, referred to as the modern cloudmonkey, is a simplified
Go port of the original tool and ships as a standalone executable for several
targets such as Linux, Mac and Windows.

### License

Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
