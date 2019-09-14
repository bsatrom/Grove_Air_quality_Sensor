<<<<<<< HEAD
## Grove Air Quality Sensor
-------------------------------------------------------------
![](https://statics3.seeedstudio.com/images/101020021%201.jpg)

[Grove Air Quality Sensor](https://www.seeedstudio.com/Grove-Air-quality-sensor-p-1065.html)

This sensor is designed for comprehensive monitoring of indoor air conditions.
It's responsive to a wide scope of harmful gases such as carbon monoxide, alcohol, acetone, thinner, formaldehyde and so on.
Due to the measuring mechanism, this sensor can not output specific data to describe target gases' concentrations quantitatively.
But it's still competent enough to be used in applications that require only qualitative results, like auto refresher sprayers and auto air cycling systems.

For more information, please refer to the [wiki page][1]

----
This software is written by Bruce Qin for Seeed Studio<br>
and is licensed under [The MIT License](http://opensource.org/licenses/mit-license.php). Check license.txt for more information.<br>

Contributing to this software is warmly welcomed. You can do this basically by<br>
[forking](https://help.github.com/articles/fork-a-repo), committing modifications and then submitting a [pull request](https://help.github.com/articles/using-pull-requests) (follow the links above<br>
for operating guide). Adding change log and your contact into file header is encouraged.<br>
Thanks for your contribution.

Seeed Studio is an open hardware facilitation company based in Shenzhen, China. <br>
Benefiting from local manufacturing power and a convenient global logistic system, <br>
we integrate resources to serve a new era of innovation. Seeed also works with <br>
global distributors and partners to push the open hardware movement.<br>


[1]:http://wiki.seeedstudio.com/Grove-Air_Quality_Sensor_v1.3


[![Analytics](https://ga-beacon.appspot.com/UA-46589105-3/Grove_Air_quality_Sensor)](https://github.com/igrigorik/ga-beacon)
=======
# Grove_Air_quality_Sensor

A Particle library for Grove_Air_quality_Sensor

## Welcome to your library!

To get started, modify the sources in [src](src). Rename the example folder inside [examples](examples) to a more meaningful name and add additional examples in separate folders.

To compile your example you can use `particle compile examples/usage` command in [Particle CLI](https://docs.particle.io/guide/tools-and-features/cli#update-your-device-remotely) or use our [Desktop IDE](https://docs.particle.io/guide/tools-and-features/dev/#compiling-code).

Libraries can also depend on other libraries. To add a dependency use [`particle library add`](https://docs.particle.io/guide/tools-and-features/cli#adding-a-library) or [library management](https://docs.particle.io/guide/tools-and-features/dev/#managing-libraries) in Desktop IDE.

After the library is done you can upload it with `particle library upload` or `Upload` command in the IDE. This will create a private (only visible by you) library that you can use in other projects. If you wish to make your library public, use `particle library publish` or `Publish` command.

_TODO: update this README_

## Usage

Connect XYZ hardware, add the Grove_Air_quality_Sensor library to your project and follow this simple example:

```
#include "Grove_Air_quality_Sensor.h"
Grove_Air_quality_Sensor grove_Air_quality_Sensor;

void setup() {
  grove_Air_quality_Sensor.begin();
}

void loop() {
  grove_Air_quality_Sensor.process();
}
```

See the [examples](examples) folder for more details.

## Documentation

TODO: Describe `Grove_Air_quality_Sensor`

## Contributing

Here's how you can make changes to this library and eventually contribute those changes back.

To get started, [clone the library from GitHub to your local machine](https://help.github.com/articles/cloning-a-repository/).

Change the name of the library in `library.properties` to something different. You can add your name at then end.

Modify the sources in <src> and <examples> with the new behavior.

To compile an example, use `particle compile examples/usage` command in [Particle CLI](https://docs.particle.io/guide/tools-and-features/cli#update-your-device-remotely) or use our [Desktop IDE](https://docs.particle.io/guide/tools-and-features/dev/#compiling-code).

After your changes are done you can upload them with `particle library upload` or `Upload` command in the IDE. This will create a private (only visible by you) library that you can use in other projects. Do `particle library add Grove_Air_quality_Sensor_myname` to add the library to a project on your machine or add the Grove_Air_quality_Sensor_myname library to a project on the Web IDE or Desktop IDE.

At this point, you can create a [GitHub pull request](https://help.github.com/articles/about-pull-requests/) with your changes to the original library. 

If you wish to make your library public, use `particle library publish` or `Publish` command.

## LICENSE
Copyright 2019 Seeeed Studio, Brandon Satrom <brandon@particle.io>

Licensed under the <insert your choice of license here> license
>>>>>>> initial particle library config
