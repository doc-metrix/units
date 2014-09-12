Units
===

> Specification of units found in metric specifications.


## Table of Contents

1. 	[Units](#units)
	-	[Current](#current)
		* 	[A](#a)
	- 	[Voltage](#voltage)
		*	[V](#v)
	- 	[Temperature](#temperature)
		*	[C](#c)
	-	[Digital Information](#digitial-information)
		*	[KB](#kb)
		*	[KiB](#kib)
		*	[MB](#mb)
		*	[MiB](#mib)
		*	[GB](#gb)
		*	[GiB](#gib)
		* 	[MB/s](#mbs)
	- 	[Memory](#memory)
		*	[hugepages](#hugepages)
	- 	[Time](#time)
		*	[ms](#ms)
		*	[s](#s)
	- 	[Other](#other)
		* 	[I/O](#io)
		*	[rpm](#rpm)
		*	[utilization](#utilization)
1. 	[Contributing](#contributing)
1. 	[Usage](#usage)
	-	[Bower](#bower)
1. 	[License](#license)


## Units

A metric may have one of the following units... 


===
### Current

#### A

[ampere](http://en.wikipedia.org/wiki/Ampere): the amount of electric charge passing a point in an electric circuit per unit time.


===
### Voltage

#### V

[volt](http://en.wikipedia.org/wiki/Volt): the difference in electric potential between two points of a conducting wire when an electric current of one ampere dissipates one watt of power between those points.


===
### Temperature

#### C

[Celsius](http://en.wikipedia.org/wiki/Celsius): unit of measurement for temperature.


===
### Digital Information

#### KB

[kilobytes](http://en.wikipedia.org/wiki/Kilobyte): 1 `kilobyte` consists of 1000 `bytes`.


#### KiB

[kibibyte](http://en.wikipedia.org/wiki/Kibibyte): 1 `kibibyte` consists of 1024 `bytes`.


#### MB

[megabytes](http://en.wikipedia.org/wiki/Megabyte): 1 `megabyte` consists of 1e6 `bytes`.


#### MiB

[mebibyte](http://en.wikipedia.org/wiki/Mebibyte): 1 `mebibyte` consists of 1024^2 `bytes`.


#### GB

[gigabyte](http://en.wikipedia.org/wiki/Gigabyte): 1 `gigabyte` consists of 1e9 `bytes`.


#### GiB

[gibibyte](http://en.wikipedia.org/wiki/Gibibyte): 1 `gibibyte` consists of 1024^3 `bytes`.


#### MB/s

[megabytes](http://en.wikipedia.org/wiki/Megabyte) per second: 1 `megabyte` consists of 1e6 `bytes`.


===
### Memory

#### hugepages

[hugepages](http://en.wikipedia.org/wiki/Page_(computer_memory)#Huge_pages): number of pages in memory that are larger than the default page size.


===
### Time

#### ms

milliseconds: unit of measurement for time.


#### s

seconds: unit of measurement for time.


===
### Other


#### I/O

I/O: input and output.


#### rpm

rpm: revolutions per minute.


#### utilization

utilization: describes a unitless value indicating the extent to which a device is utilized.



===
## Contributing

To contribute to the data-type specification, see the contributing [guide](https://github.com/doc-metrix/contributing). Any updates to the specification should be tagged.

``` bash
$ git tag -a <major.minor.patch> -m "[UPDATE] version."
$ git push origin <major.minor.patch>
```

Use [semantic versioning](http://semver.org/) (semvar) for communicating versions.

*	Any new units should be communicated as `minor` updates.
*	Any corrections/value modifications should be `patches`.
* 	Any specification restructuring (changing field names, removing fields, etc) should be communicated as a `major` update.


===
## Usage

The specification is stored as [JSON](http://json.org/), a lightweight data-interchange format. Many languages provide JSON support: [JavaScript](http://www.json.org/js.html), [Python](https://docs.python.org/2/library/json.html), [Go](http://golang.org/pkg/encoding/json/), [PHP](http://php.net/manual/en/book.json.php), [Java](http://json.org/java/), [Haskell](http://hackage.haskell.org/package/json), and [others](http://json.org/).

You are free to use the JSON specification, as is. Simply copy the file and use accordingly.

For those using package managers to manage dependencies, we provide package manager support, as outlined below.


### Bower

The specification is registered as a [Bower](http://bower.io) package. Bower provides a straightforward means for managing dependencies.

In order to use Bower, you must first install [Node.js](http://nodejs.org/) and [Git](http://git-scm.com/book/en/Getting-Started-Installing-Git). Once the prerequisites are installed,

``` bash
$ npm install -g bower
```

To [install](http://bower.io/docs/api/#install) the latest specification,

``` bash
$ bower install doc-metrix-units
```

Bower will place the specification in a `bower_components/` directory within the current working directory.

To [update](http://bower.io/docs/api/#update) to the latest specification,

``` bash
$ bower update doc-metrix-units
```


## License

[MIT license](http://opensource.org/licenses/MIT). 


---
## Copyright

Copyright &copy; 2014. NodePrime.

