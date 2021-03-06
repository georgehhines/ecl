# ECL

**Very lightweight Estimation & Control Library.**

[![DOI](https://zenodo.org/badge/22634/PX4/ecl.svg)](https://zenodo.org/badge/latestdoi/22634/PX4/ecl) [![Build Status](https://travis-ci.org/PX4/ecl.svg?branch=master)](https://travis-ci.org/PX4/ecl)

This library solves the estimation & control problems of a number of robots and drones. It accepts GPS, vision and inertial sensor inputs. It is extremely lightweight and efficient and yet has the rugged field-proven performance.

The library is currently BSD licensed, but might move to Apache 2.0.
## Building EKF Library

### Prerequisites:

  * Eigen3: http://eigen.tuxfamily.org/index.php installed

#### Ubuntu:

```
sudo apt-get install libeigen3-dev
```

#### Mac

```
brew install eigen
```


By following the steps mentioned below you can create a shared library which can be included in projects using `-l` flag of gcc:

```
mkdir Build/
cd Build/
cmake ../EKF
make
```

Alternatively, just run:

```
./build.sh
```
