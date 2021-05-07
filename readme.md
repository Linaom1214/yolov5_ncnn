## 基于ncnn的yolov5部署

```powershell
export ncnn_DIR={yourncnnpath}/ncnn/build/install/lib/cmake/ncnn
mkdir build
cd build
cmake ..
make -j8
```

## 环境 

+ ubuntu20.04

+ opencv 3.1.3

+ ncnn 

## Tips 
make sure file {yolov5.param yolov5.bin} in **build** file or with the file  yolov5_demo in same file

