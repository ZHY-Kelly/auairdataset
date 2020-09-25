

# AU-AIR Dataset API

## News
**16.09.2020**
- Researchers from Fraunhofer IOSB in Ettlingen have released a subset of the AU-AIR dataset, namely *AU-AIR-Track*. AU-AIR-Track contains:
	- Two images sequences ranging from 887 frames and 512 frames, containing respectively 63 and 27 annotated objects.  
	- Annotations for visual object tracking, with occlusion (also annotated).  
	- Two 3D reconstructions for each image sequence, and pseudo depth maps associated with the camera poses.
 [Paper](https://arxiv.org/abs/2008.02834),  [Dataset and Tools](https://drive.google.com/file/d/1tDk12BwDdrQp7eFcnONSpjkpvnrNxJx3/view?usp=sharing)

**15.09.2020**
- We have updated the annotation file to improve annotations. The new link can be found in "Download" section below.
- We have also released a json file for [VGG Image Annotator](http://www.robots.ox.ac.uk/~vgg/software/via/) to edit annotations. Feel free to customize annotations for your research. You can download AU-AIR VIA annotations [here](https://drive.google.com/file/d/1OGAbPMddQKgZ99VzRO91__d9SfnkclHK/view?usp=sharing).


## Dataset
The AU-AIR is a multi-modal aerial dataset captured by a UAV. Having visual data, object annotations, and flight data (time, GPS, altitude, IMU sensor data, velocities), AU-AIR meets vision and robotics for UAVs.

https://bozcani.github.io/auairdataset

![alt text](https://raw.githubusercontent.com/bozcani/auairdataset/master/intro.jpg) 

### Specifications
- 8 raw RGB videos (more than 2 hours in total)
- 32,283 extracted and labelled frames
- Bounding box annotations for eight objects related to traffic:
	- human, car, van, truck, bike, motorbike, bus, trailar
- Time, GPS, altitude, IMU sensor data and linear velocities of the drone are avaliable for each extracted frame.

### Download
Please download both the AU-AIR images and annotations to run the demo and use the API:

Images: https://drive.google.com/open?id=1pJ3xfKtHiTdysX5G3dxqKTdGESOBYCxJ (2.2 GB)

Annotations **(V.1.1)**: https://drive.google.com/file/d/1GyoBK-NalDFfAtRt9LO6FBujbObyaZLv/view?usp=sharing (55 MB)

## Dependencies
You will need common dependencies like `numpy` and `opencv`.

## Installation
To install the package from source, simply clone or download the repository to your machine
`git clone https://github.com/bozcani/auairdataset`

`cd auairdataset`

`python setup.py install`

## References

I. Bozcan and E. Kayacan, "AU-AIR: A Multi-modal Unmanned Aerial Vehicle Dataset for Low Altitude Traffic Surveillance", IEEE International Conference on Robotics and Automation (ICRA) 2020.


