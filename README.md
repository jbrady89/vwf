# Virtual World Framework

The Virtual World Framework (VWF) allows you to build collaborative, immersive applications in the browser. VWF provides:

- Realtime state synchronization.
- Support for immersive applications - a set of drivers for 3D, audio, video and modern graphics.

VWF applications are written in JavaScript and leverage emerging web technologies such as WebGL, WebRTC, and WebSockets to provide a full 3D environment that is automatically synchronized across clients.

## Installation

**Install on Mac/Linux**

NOTE: On Mac OS X, please make sure you have Xcode Command Line Tools installed prior to executing the script below (https://developer.apple.com/xcode/).

```
$ curl -kL http://get.virtual.wf  | sh
```

This command may be re-run to upgrade the installation to the latest version of VWF.

**Install on Windows**

- Download the latest VWF Baseline and extract the zip. (http://download.virtualworldframework.com/files/VWF_Windows_latest.zip)

- Execute VWF from the root folder at a command prompt. IE.  c:\vwf-extracted-folder>vwf

- Follow the instructions prompted to setup your environment.

For more complex installations, such as working on VWF core, please see our [Installation Instructions](http://www.virtual.wf/web/docs/install.html).

## Quick Start 

**Mac/Linux**

Create a new VWF application.

```
$ vwf create my-app
```

Change directory into that app and run the application.

```
$ cd my-app
$ vwf
```

Your application is now up and running at
[http://localhost:3000](http://localhost:3000).

To get started with VWF, check out [Getting
Started](http://virtual.wf/web/docs/readme.html).

**Windows** 

Execute the _run.bat_ file provided at the root level of the extracted folder.

```
c:\vwf> vwf create my-app
c:\vwf> cd my-app
c:\vwf\my-app> vwf
```

Your application is now up and running at [http://localhost:3000](http://localhost:3000).

## Examples

For examples, check out our [demos](http://www.virtual.wf/web/catalog.html).

Also, browse through other example applications in the `public` folder of your
local VWF repository.

## Contributing

Our development process utilizes several branches:

* `master`                - Stable release of VWF. Running on http://virtual.wf.
* `integration`           - Integration testing features from development before merging into master. Running on http://integration.virtual.wf.
* `development`           - The latest development and new features of the framework. Running on http://development.virtual.wf.
* `branch/feature-name`   - Feature development is done on a feature branch before being merged back to development.

When submitting a pull request, please use the `development` branch.

Also, please be sure that your pull request conforms to our [Coding Standard](http://redmine.virtualworldframework.com/projects/vwf/wiki/JavaScript_Coding_Standard).

##Current Build Status
Master Branch - [![Build Status](http://jenkins.virtualworldframework.com/job/Master/badge/icon)](http://jenkins.virtualworldframework.com/job/Master/)      Integration Branch - [![Build Status](http://jenkins.virtualworldframework.com/job/Integration/badge/icon)](http://jenkins.virtualworldframework.com/job/Integration/)      Development Branch - [![Build Status](http://jenkins.virtualworldframework.com/job/Development/badge/icon)](http://jenkins.virtualworldframework.com/job/Development/)

## Community

Keep track of developments and get help with VWF.

- Discover an issue? Head over to [Issues](https://github.com/virtual-world-framework/vwf/issues) and report it.
- Have a question about VWF? Ask away on [our forum](http://www.virtual.wf/web/forum.html).

## License

Copyright 2013 United States Government, as represented by the Secretary of Defense, Under Secretary of Defense (Personnel & Readiness) licensed under the [Apache 2.0 License](https://github.com/virtual-world-framework/vwf/blob/master/LICENSE).
