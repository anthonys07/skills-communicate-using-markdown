# Daily Learning (Heading 1) 
## Morning Planning (Heading 2) 
- [ ] Check out github blog 
- [ ] Learn about github pages 
- [ ] Convert my first blog post into an actual webpage
- These are what the walkthrough tells me to do
## Review (Heading 2) 
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
