# ncnn-android-yolov5

The YOLOv5 object detection

this is a sample ncnn android project, it depends on ncnn library only

https://github.com/Tencent/ncnn

## how to build and run
### step1
https://github.com/Tencent/ncnn/releases

download ncnn-android-vulkan.zip or build ncnn for android yourself

### step2
extract ncnn-android-vulkan.zip into app/src/main/jni or change the ncnn_DIR path to yours in app/src/main/jni/CMakeLists.txt

### step3
open this project with Android Studio, build it and enjoy!

## screenshot
![](screenshot.jpg)


## Questions


1. Could Not find Vulkan

https://github.com/nihui/ncnn-android-yolov5/issues/10 

minSdkVersion is no older than 24

