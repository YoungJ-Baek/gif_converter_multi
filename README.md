## accomplished

- use video trimmer example app to load video and call ffmpeg command
- add operations
  - convert video into gif file
  - save gif file into gallery

## todo

- get meta data of video and use it as framerate and resolution
  - flutter_video_info
  - ffmpeg function
- make load multiple videos button and page
  - page includes progress bar and status (current num/total num)
  - when finish current state, update progress and setstate
- overwrite video file into gif file
  - maintain meta data of video file so that it does not ruin the order
- test with iphone, not a simulator
