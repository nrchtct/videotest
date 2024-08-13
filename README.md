
## Host video files >100MB from GitHub repo to play in webpage

1. Add git-lfs support. E.g., on macOS using homebrew:

`brew install git-lfs`

2. Enable lfs for a repo
   
`cd /path/to/repo`  
`git lfs install`

3. Specify file extension for videos:

`git lfs track "*.mp4"`

4. Link to video file directly:

`https://media.githubusercontent.com/media/username/repo/branch/path/to/video.mp4`

## See example: https://nrchtct.github.io/videotest/

