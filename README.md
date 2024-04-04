# Upload video thumbnails

## Instructions for uploading the ~3-5 second video thumbnail clips. 

### 1. Export the video clip
- Use these exact settings:
  - Container: .MP4
  - Codec: H264
  - Resolution: 1920 x 1080 px maximum
  - Sound: disable sound export with the video clip
  - Length: 3-5 seconds
  - bitrate and file size: ~2000 kbps - file size of max. 1 MB

### 2. Rename the video clip
- Rename to this template: preview_projectname_01.mp4
  - Example: preview_fisker_01.mp4

### 3. Upload to GitHub
- github "Add Files" --> "Upload Files

### 4. Copy and paste filename into Webflow
- Copy the filename and add the following in front of the link: https://cdn.jsdelivr.net/gh/aaronnossek/vandermerwe/
  - Example: https://cdn.jsdelivr.net/gh/aaronnossek/vandermerwe/preview_fisker_01.mp4
  - You can check if it works by opening this link in your browser. A simple video player with your video clip should appear.

- Paste the video link into the project's Webflow CMS "Thumbnail Video Link" input field. Publish and done.

#Edit the Website
https://www.vandermerwe.eu/?edit
