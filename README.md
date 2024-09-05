## Introduction

SSP is a Simple Stream Protocal to get video/audio stream from Z CAM cameras.

## Why we use SSP?
Z CAM build VR cameras, to sync the video frame via network from different camera, we need to add some meta info on each video/audio frame.

The protocal inside is very straight forward, it's TCP based.

## Features
- Win10/Linux x64 is supported
- C++ 11
- Video/Audio timestamp
- H.265/H.264 are supported
- AAC/PCM are supported

## How to use it
Take a look at the example code.

Note:

In the OnH264DataCallback/OnAudioDataCallback callback, please make a copy for your media data.

add python call version
