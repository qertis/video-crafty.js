video-crafty.js
===============

## HTML5 Video crafty.js module

### How to use.
Insert script video-crafty.js on your html5 page
After Crafty.init write for FullScreenStyle:

```javascript
  Crafty.e('Video').attr({
    poster: 'your_poster.jpg', //optional
    videos: {
      webm: 'your_video.webm',//optional
      mp4: 'your_video.mp4'
    },
    once: true //optional (default is false)
  }).createVideo()
    .setFullScreenStyle() // or setInnerScreenStyle
  ;
```
  
### DEMO:
InnerVideo: would be later :)  <br>
FullVideo: http://codepen.io/qertis/full/mIgzf/
