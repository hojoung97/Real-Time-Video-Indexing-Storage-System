# Real Time Video Indexing Storage System
Purdue Research Team CAM2 Summer 2019 Project

CAM2 Image database team have been working on real time video indexing system. The project is currently work-in-progress with research paper aimed to be completed.

Source code: https://github.com/PurdueCAM2Project/CAM2ImageDatabase

## Overview
The project aims to process incoming video streams from multiple IP cameras around the world, extract features from the frames, store the images as objects along with corresponding features, and make them ready for user query.

## Key Technology

### Database
#### [Vitess](https://github.com/vitessio)
A database clustering system for horizontal scaling of MySQL
#### [MinIO](https://github.com/minio)
MinIO is a cloud storage server released under Apache License v2, compatible with Amazon S3.
As an object store, MinIO can store unstructured data such as photos, videos, log files, backups and container / VM images. The maximum size of an object is 5TB.

### Object Detection
#### YOLOv3

![System Design](/images/overall.png)

## More to be updated...
Our team is currently wrting a research paper, so more information is to be updated once our research paper is released. I really want to show more on here, but I am afraid to write information public just yet. Our research paper topic is on "Enabling Large-Scale and Real-Time Feature Indexing on Live Video Stream". I will try to update any good information whenever I can.

