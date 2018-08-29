# TensorflowJS posenet study project
It is my study project of TensorflowJS posenet.
https://github.com/tensorflow/tfjs-models/tree/master/posenet

## Note
1. Try to load video from other server, but estimateMultiplePoses not work. Fund out the video must save in same server.
2. Adjust scoreThreshold to 0.7. The skeletons in video output became much stable.

## Install
    npm install
    
## Start
Start development server on http://localhost:8080<br>
Browser will auto reload when js, scss, html changed.

    gulp

## Build

    gulp build

- Copy all files to ./build folder.
- Copy all files to ../htdocs/website/static folder

