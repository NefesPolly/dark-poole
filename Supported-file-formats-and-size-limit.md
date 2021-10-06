---
layout: page
title: Supported file formats and size limit
categories: [support]
---

Please follow these technical guidelines when submitting your artwork to Throne:
* The main uploaded artwork can be in JPG, PNG, GIF, or MP4, up to 50 MB. The ideal width for still images is 3000 pixels.
* The best resolution for video is 1080p or 4K.
* Mobile devices may have trouble loading videos that are larger than 2700px in both dimensions

<br/>

## What causes the size of video files to increase?
Video length
* The longer the video, the more data it will occupy

Video resolution e.g 720, 1080, 2k, 4k
* The more pixels a frame of video has, the bigger the file size will be

Framerate e.g 30fps, 60fps
* Frame rate is the number of frames used per second of video, the higher the frame rate, the bigger the file size

Bitrate e.g 2mbps, 10mbps, 30mbps
* Bitrate indicates the amount of video data processed for a second of footage. The higher the bitrate, the more detail you will see in the video, but also the bigger the video will be.
* It is the main source of "bad looking" videos, where you see artifacts and frames that block and tear.

Codec e.g h264, AV1
* An encoding format is the means of converting video data into a format that can be viewed on a variety of devices. When video codecs encode video, they remove information from the original video footage that the codec determines will not be noticeable to the viewer. A codec's algorithm determines the compression, the quality and size of the output.

<br/>

## Keeping file sizes under 50MB while creating captivating content
* You have to decide what resolution you want your raw footage to be in once you have it. A suggestion is between 1080p and 2K, but bear in mind that larger resolutions need higher bitrates to look good.
* Frame rate is the next consideration, 30 or 60 frames per second should be fine, but higher frame rates will result in a larger file.
* The next contributing factor is Bitrate. At low bitrates, you will see blocky/blurry footage in the final product. Any bitrate higher than 36mbps will add significant file size to the output but will be perceived as lossless.
* The final component is the codec; if you want your original asset to be played natively in current browsers, you should use a codec and container format that is widely supported, such as an MP4 container using H.264 video and AAC as audio.
* In order to guarantee playback on Throne, we generate additional assets by running the source video through a transcoder to generate web playable assets. We cap the bitrate of these assets to 36Mbps. The videos are H264 coded MP4 files with AAC audio. The original asset is not affected by this at all as these are copies for use within the web application. The original asset is stored immutably on the IPFS.

<br/>
