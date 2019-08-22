CISFW
=====

OpenCV Implementation based on "Canonical Image Selection from the Web, Yushi Jung."


http://opencv-java-tutorials.readthedocs.io/en/latest/01-installing-opencv-for-java.html#introduction-to-opencv-for-java
https://www.pyimagesearch.com/2016/12/19/install-opencv-3-on-macos-with-homebrew-the-easy-way/

sudo xcode-select --install
brew edit opencv
-DBUILD_opencv_java=ON
brew install --build-from-source opencv

Add as external jar:
/usr/local/Cellar/opencv/3.3.1_1/share/OpenCV/java/opencv-330.jar

Add as native library location in build path:
/usr/local/Cellar/opencv/3.3.1_1/share/OpenCV/java/

Setup eclipse
mvn eclipse:eclipse
