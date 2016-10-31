## notes for glp

Stack post that hones in on "Hough Transforms":<br>
http://stackoverflow.com/questions/6555629/algorithm-to-detect-corners-of-paper-sheet-in-photo

Install OpenCV and tutorial for detection:<br>
http://www.pyimagesearch.com/2015/06/22/install-opencv-3-0-and-python-2-7-on-ubuntu/

Another installation option:<br>
http://embedonix.com/articles/image-processing/installing-opencv-3-1-0-on-ubuntu/

**Note:** Make sure to set this to "OFF", `-D INSTALL_C_EXAMPLES=OFF`

Per...
<pre><code>Update (3 January 2016): In order to build OpenCV 3.1.0 , you need to set -D INSTALL_C_EXAMPLES=OFF  (rather than ON ) in the cmake  command. There is a bug in the OpenCV v3.1.0 CMake build script that can cause errors if you leave this switch on. Once you set this switch to off, CMake should run without a problem.</code></pre>

**Note:** The mask created in the tutorial is an image!  If you look at the pixels, it appears to be 0's and 255's, where 255 would be a battleship "hit".  Interesting.  We should convert to image and "see" the countours.
