CXX=g++
FLAGS=-o cc -std=c++11  *.cpp
LIB=/home/henok/opencv/lib64/libopencv_highgui.so /home/henok/opencv/lib64/libopencv_imgproc.so /home/henok/opencv/lib64/libopencv_core.so /home/henok/opencv/lib64/libopencv_imgcodecs.so /home/henok/opencv/lib64/libopencv_videoio.so 
INC=$(OPENCV_INCLUDE)

all:
	$(CXX)  $(FLAGS) $(LIB) &> build_output.log
install:
	mkdir build
	cp cc ../../../../cc/build
	cp $(LIB) ../../../../cc/build
clean: 
	rm -f cc *.o
