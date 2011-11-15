# ganpuku
ganpuku(眼福) is a video player library. it supports html5/youtube/vimeo.

## usage
```javascript
var video = $('#video').ganpuku('http://www.youtube.com/watch?v=example');
var player = video.player;
player.play();
player.pause();
player.mute();
player.unmute();
video.on('ready', function(){ video.player.play(); });
video.on('play', function(){ console.log('start'); });
video.on('pause', function(){ console.log('stop'); });
video.on('end', function(){ console.log('finish'); });
video.change('http://vimeo.com/example');
video.change('http://example.com/example.mp4');
```

## License

(The MIT License)

Copyright (c) 2011 myatsumoto &lt;myatsumoto@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

