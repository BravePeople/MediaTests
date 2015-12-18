# Media Tests

#### Purpose
To deliver the same high-quality feeling on mobile and slow connections that we design on the desktop.

#### Libraries in use:


[Picturefill](https://github.com/scottjehl/picturefill) - Responsive image polyfills, allowing images to be set to different sizes based on media queries

[A dynamic image CDN](https://www.imgix.com/) - Leverages CDN funcitonality and offloading resizing, only maintaining master copies of imagery

[videojs](http://videojs.com/) - extending the video tag further - currently unimplemented


---

#### Findings:

- Video backgrounds rarely use any audio. By disabling the audio track entirely, you can save megabytes off a ten second video with a silent track.
