# OpenCV GStreamer Build
OpenCV 4.10 wheel built with GStreamer support. Tested on Python 3.10 but should work on 3.8+ python versions on Windows. Using GStreamer OpenCV can read camera at higher FPS and less latency and much more.

The wheel also contains minimal GStreamer library which supports camera capture using MF or DSHOW and it should be used automatically so you don't have to download GStreamer and link to it separately. If you want more GStreamer features, modify __init__.py in the cv2 package (located in your python environment folder) to load your own GStreamer version.

To install, run:
```bash
git clone https://github.com/Reblexis/opencv-gstreamer-build.git
pip uninstall opencv-python -y
pip install numpy
pip install --no-index opencv-gstreamer-build\opencv_python_gstreamer-4.10.0.0+gst-py3-none-any.whl
```


## Licensing
You can you this wheel as you please, however keep in mind that GStreamer is licensed under the LGPL license.
