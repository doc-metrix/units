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
		*	[GB](#gb)
		* 	[MB/s](#mb-s)
	- 	[Memory](#memory)
		*	[hugepages](#hugepages)
	- 	[CPU](#cpu)
		*	[processes and threads](#processes-and-threads)
	- 	[Time](#time)
		*	[ms](#ms)
		*	[s](#s)
	- 	[Other](#other)
		* 	[I/O](#i-o)
		*	[RPM](#rpm)
		*	[reads](#reads)
		*	[sector](#sectors)
		*	[write](#writes)
		*	[utilization](#utilization)


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

[celsuis](http://en.wikipedia.org/wiki/Celsius): unit of measurement for temperature.


===
### Digital Information

#### KB

kilobyte: 1024 bytes.


#### GB

gigabyte: 1,073,741,824 bytes.


#### MB/s

megabytes per second: 1,048,576 byte per second.

===
### Memory

#### hugepages

Number of pages in memory that are larger than the default page size.


===
### CPU

#### processes and threads

Number of CPU processes and threads.


===
### Time

#### ms

milliseconds: unit of measurement for time.


#### s

seconds: unit of measurement for time.


===
### Other


#### I/O

Input and output.


#### RPM

Revolutions per minute.


#### reads

Number of reads; e.g., number of reads from a disk.


#### sectors

Number of sectors; e.g., number of sectors on a disk.


#### writes

Number of writes; e.g., number of writes from a disk.


#### utilization

Describes a unitless value indicating the extent to which a device is utilized.



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

