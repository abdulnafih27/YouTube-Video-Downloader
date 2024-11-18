# YouTube-Video-Downloader


# YouTube Video Downloader Script

This is a simple Python script that allows you to download YouTube videos, audio, and videos with subtitles using the `yt-dlp` library. The script provides options to choose video resolutions, download audio in MP3 format, and even download subtitles in English.

## Features

1. **Download Video**: Allows you to download the video in a selected resolution and format.
2. **Download Audio**: Downloads only the audio in MP3 format.
3. **Download with Subtitles**: Downloads video along with English subtitles.

## Requirements

- Python 3.x
- `yt-dlp` library (a more feature-rich fork of `youtube-dl`)
- `ffmpeg` (for processing video and audio)

### Install Dependencies

To install the necessary Python packages, run the following command:

```bash
pip install yt-dlp
```

Additionally, you will need `ffmpeg` for video and audio processing. Download `ffmpeg` from [FFmpeg's official website](https://ffmpeg.org/download.html) and make sure it is properly set up in your system path.

### Usage

1. Clone or download this repository.
2. Place the script in a directory of your choice.
3. Modify the `ffmpeg_path` variable in the script to point to the location where `ffmpeg` is installed on your system.

#### Running the Script

To run the script, execute it from your terminal or command prompt:

```bash
python ytDownloader.py
#Create a YoutubeVideos folder in the LocalDisk :C 
```

### Script Flow:

1. **Prompt for Choice**: The script asks you to choose one of the following options:
   - Download Video
   - Download Audio
   - Download Video with Subtitles
2. **Input Video URL**: After choosing an option, you'll be prompted to enter the URL of the YouTube video you wish to download.
3. **Choose Resolution**: If downloading a video, you will be shown a list of available resolutions for the video. Select the resolution you prefer.
4. **Download**: After making your selections, the script will start downloading the video or audio based on your choices.

### Example Output:

```bash
Welcome to YouTube Downloader!
1. Download Video
2. Download Audio
3. Download with Subtitles
Enter your choice (1/2/3): 1
Enter the Video URL: https://www.youtube.com/watch?v=exampleID
Available resolutions:
1. 1080p mp4
2. 720p mp4
Choose the resolution (enter number): 1
Download Completed!
```

The video will be saved to the specified download directory: `C:/YoutubeVideos`.

## Learning Purpose

This script was created as a learning exercise to explore the use of Python for interacting with web APIs, handling video downloads, and using the `yt-dlp` library. It demonstrates basic file management, error handling, and interaction with external libraries. Please use this script responsibly and ensure that you are complying with YouTube's Terms of Service.

## License

This project is for educational purposes only. It is not intended for commercial use or illegal distribution of copyrighted content. Use this script at your own risk.

---

Feel free to contribute or improve this script by creating a pull request or providing feedback.
```

You can now copy and paste this directly into your `README.md` file on GitHub. It includes all the necessary instructions, features, and licensing details for your project.