# Audio and Video Element

## Video

The **`<video>`** HTML element embeds a media player which supports video playback into the document

Example

```
    <video src="./video.mp4" controls></video>
```

### Attributes of a video element

| Attribute    | Description                                                                                           | Example                                                                |
| ------------ | ----------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| src          | Specifies the URL of the video file                                                                   | `<video src="example.mp4"></video>`                                    |
| controls     | Specifies whether video controls should be displayed                                                  | `<video src="example.mp4" controls></video>`                           |
| autoplay     | Specifies that the video should start playing automatically                                           | `<video src="example.mp4" autoplay></video>`                           |
| loop         | Specifies that the video should start over again when it reaches the end                              | `<video src="example.mp4" loop></video>`                               |
| muted        | Specifies that the audio output of the video should be muted                                          | `<video src="example.mp4" muted></video>`                              |
| preload      | Specifies how the video should be loaded when the page loads                                          | `<video src="example.mp4" preload="auto"></video>`                     |
| width        | Specifies the width of the video element (in pixels or %)                                             | `<video src="example.mp4" width="640"></video>`                        |
| height       | Specifies the height of the video element (in pixels or %)                                            | `<video src="example.mp4" height="360"></video>`                       |
| poster       | Specifies an image to be shown while the video is downloading, or until the user hits the play button | `<video src="example.mp4" poster="video-poster.jpg"></video>`          |
| controlsList | Specifies the set of controls to be shown on the video element                                        | `<video src="example.mp4" controls controlsList="nodownload"></video>` |
| crossorigin  | Specifies how crossorigin requests are handled for the video element                                  | `<video src="example.mp4" crossorigin="anonymous"></video>`            |
| playsinline  | Specifies that the video should play inline, instead of fullscreen, on iOS devices                    | `<video src="example.mp4" playsinline></video>`                        |

## Audio

The **`<audio>`** HTML element is used to embed sound content in documents. It may contain one or more audio sources, represented using the src attribute or the **`<source>`** element: the browser will choose the most suitable one.

```
    <audio controls src="./audio.mo3"></audio>
```

### Attributes:-

| Attribute    | Description                                                       | Example                                                              |
| ------------ | ----------------------------------------------------------------- | -------------------------------------------------------------------- |
| src          | Specifies the URL of the audio file                               | `<audio src="audio.mp3"></audio>`                                    |
| controls     | Specifies whether audio controls should be displayed              | `<audio src="audio.mp3" controls></audio>`                           |
| autoplay     | Specifies whether the audio should start playing automatically    | `<audio src="audio.mp3" autoplay></audio>`                           |
| loop         | Specifies whether the audio should start over again when finished | `<audio src="audio.mp3" loop></audio>`                               |
| preload      | Specifies how the audio file should be loaded when the page loads | `<audio src="audio.mp3" preload="auto"></audio>`                     |
| muted        | Specifies whether the audio should be muted                       | `<audio src="audio.mp3" muted></audio>`                              |
| volume       | Specifies the volume of the audio (0.0 to 1.0)                    | `<audio src="audio.mp3" volume="0.5"></audio>`                       |
| crossorigin  | Specifies how audio should be handled in terms of CORS            | `<audio src="audio.mp3" crossorigin="anonymous"></audio>`            |
| controlsList | Specifies which audio controls should be displayed                | `<audio src="audio.mp3" controls controlsList="nodownload"></audio>` |
| currentTime  | Specifies the current playback position in seconds                | `<audio src="audio.mp3" currentTime="10"></audio>`                   |
| playbackRate | Specifies the speed at which the audio should be played           | `<audio src="audio.mp3" playbackRate="1.5"></audio>`                 |
| poster       | Specifies an image to display while the audio is downloading      | `<audio src="audio.mp3" poster="audio-poster.jpg"></audio>`          |
| preload      | Specifies how the audio file should be loaded when the page loads | `<audio src="audio.mp3" preload="auto"></audio>`                     |
