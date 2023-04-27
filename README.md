# 📷🌎 360 Image Stitcher - Client Project

This is a project I have completed for a client. The 360 Image Stitcher is a powerful app that allows users to create immersive 360-degree images using their mobile device's camera and motion sensors. You can view a demo to the project [here](https://assets360.vercel.app/).

## 📸 Capturing Images

To capture images, users can open the app on their mobile device and follow the guide to point the camera in the desired direction. They can then start capturing images.

## 🤖 Image Stitching

Once images have been captured, they are sent to a Node.js server that uses OpenCV (with python) to stitch them together into a 360-degree image. The final image is then sent back to the frontend, ready for display.

## 📱 Compatibility

The app has been designed to work on mobile devices with motion sensors. However, please note that the app is not compatible with Safari on iOS devices. It can be used with other major browsers.
