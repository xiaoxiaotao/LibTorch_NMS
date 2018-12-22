# LibTorch_NMS
# Why I do this?

when I write A Libtorch API for detector. I find all NMS in GitHub are access to  python version. There is not The Api for Only C++ . So I do for every one when need NMS_cuda in your C++ API

# How to Work
bash make.sh  
we get libnms.so  

# Test
we give a easily example to test  
g++ -o nms  nms.cpp -L. -lnms && ./nms
