# Daily Learning

## Morning Planning
- [ ] I want to write a novel
- [ ] I want to train and run a marathon
- [ ] I want to graduate from college with a dual degree in Astronomy and Astrophysics and Aerospace Engineering

## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
