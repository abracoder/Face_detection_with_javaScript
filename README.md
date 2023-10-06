#About:
In this project you are able to get the codes required 
for face detection uaing Javascript. The codes are also 
written neatly and cleanly comments are also used to make 
understanding easy.

## Low-end Devices Bug

The video eventListener for `play` fires up too early on low-end machines, before the video is fully loaded, which causes errors to pop up from the Face API and terminates the script (tested on Debian [Firefox] and Windows [Chrome, Firefox]). Replaced by `playing` event, which fires up when the media has enough data to start playing.
