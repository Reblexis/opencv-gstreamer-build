# opencv-gstreamer-build
Opencv wheel built with gstreamer support. Tested on Python 3.10 but should work on 3.8+ python versions on Windows.

The wheel should also contain minimal gstreamer library allowing for camera capture using MF or DSHOW and should use it automatically so you don't have to create custom .dll linking. If you want more gstreamer features, modify __init__.py in the cv2 package to load your own gstreamer version.


## Licensing
You can you this wheel as you please, however keep in mind that gstreamer is licensed under LGPL.
