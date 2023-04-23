# 📝 README

This is a C++ sample program that uses the OpenCV library to capture images from a camera and display them in real time on a window.

## 🛠️ Build and Run Instructions

1. Create a directory named build in the project root directory.
2. Enter the build directory.
3. Run the command cmake .. to configure the project.
4. Run the command make to build the project.
5. Run the program with the command ./program.

## 👨‍💻 Technical Description

The program uses the VideoCapture class from OpenCV to access the camera and the Mat class to store the captured images. The imshow function is used to display the images on a window. The waitKey function is used to wait for a key pressed by the user.

The program uses the default API to open the camera and display the images in real time. If desired, the API and/or camera device can be changed by modifying the apiID and deviceID variables, respectively.

If the program is unable to open the camera, it will display an error message and terminate.

## 👍 Ready to go! You can now build and run the program.



