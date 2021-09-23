# ASR Transcoder 
ASR Transcoder Yandex Sppechkit based ASR process with GStreamer pipeline for audio source preparation.

## Getting started
### Setting up dependencies
Following dependencies are required to build the project:
 * [GStreamer](https://gstreamer.freedesktop.org/): [core](https://gitlab.freedesktop.org/gstreamer/gstreamer), [base plugins](https://gitlab.freedesktop.org/gstreamer/gst-plugins-base)  
 see the [GStreamer's documentation](https://gstreamer.freedesktop.org/documentation/installing/index.html?gi-language=c) for installation instructions
 * [amazon-s3-gst-plugin](https://github.com/amzn/amazon-s3-gst-plugin)
 * [Meson build system](https://mesonbuild.com/)
 * [AWS SDK for C++](https://aws.amazon.com/sdk-for-cpp/)
 * [parson](https://github.com/kgabis/parson)

### Building the project
```bash
$ git clone --recursive https://github.com/MaxKhlupnov/yc-speechkit-transcoder
$ cd /yc-speechkit-transcoder/src
$ cmake .
$ make
```
