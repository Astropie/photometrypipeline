
# PhotoPipe

### Photometry Pipeline for RATIR, RIMAS and LMI

PhotoPipe is a pipeline for automated reduction, photometry and astrometry, written in Python (2.7), and designed to process imaging data from the following instruments:

* [RATIR](http://butler.lab.asu.edu/RATIR/): the Reionization and Transients Infrared/Optical Project.
* [RIMAS](https://lowell.edu/research/research-facilities/4-3-meter-dct/rimas/): the Rapid infrared IMAger Spectrometer.
* [LMI](http://www2.lowell.edu/rsch/LMI/LMI.html): Large Monolitic Imager.  

This project is based on the previous versions of the pipeline by [cenko](https://github.com/cenko/RATIR-GSFC) and [vickitoy](https://github.com/vickitoy/photometry_pipeline).  
 
Built at the NASA Goddard Space Flight Center, in collaboration with the University of Maryland.
<br><br><br>
![NASA GSFC - RATIR - UMD](https://github.com/maxperry/photometrypipeline/raw/master/docs/readme-logos.jpg)

## Full Documentation

See the [Wiki](https://github.com/maxperry/photometrypipeline/wiki) for full documentation, examples, operational details and other information.


## Installation

The easiest way to get up and running with the pipeline is to download the ready-to-use **virtual machine** box and run it with Vagrant.

Alternatively, it can be installed with `pip` on Linux or macOS.  
_(**WARNING:** compiling the dependencies can take more than 6 hours.)_

#### 1) Download a pre-configured Virtual Machine

Please refer to the virtual machine [repository](https://github.com/maxperry/photometrypipeline-vm).

#### 2) Install on your machine from PyPI or git

Run `pip install --user photopipe` to install the latest stable version from [PyPI](https://pypi.python.org/pypi/photopipe). 

Or clone from `git`:

```
$ git clone git@github.com:maxperry/photometrypipeline.git
$ cd photometrypipeline/
$ python setup.py install
```

#### 3) Manual Installation
Follow the step by step instructions linked below to compile and install the pipeline and all its dependencies manually.

* [Instructions for macOS]()
* [Instructions for Linux]()

## Usage

To run the pipeline using the [sample data]() do the following:


## Bugs and Feedback

For bugs, questions and discussions please use the [Github Issues](https://github.com/maxperry/photometrypipeline/issues).


## License
This project is licensed under the GNU GPLv3 License - see the [LICENSE.md](LICENSE.md) file for details.