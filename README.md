YouTube Downloader
A compact, user-friendly desktop application for downloading YouTube videos and playlists with an elegant dark-themed interface.
<img width="607" height="508" alt="image" src="https://github.com/user-attachments/assets/b74700e1-1da4-45d6-92e5-81114de71df6" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/181a2c4f-7105-45a1-bbba-098a8ea61d7c" />


Features

🎥 Multiple Quality Options: Download videos in 4K, 1080p, 720p, 480p, or extract audio as MP3
📋 Smart Clipboard Detection: Automatically detects YouTube URLs copied to clipboard
⚡ One-Click Download: Paste and download with a single button click
📜 Download History: Keep track of your recent downloads with clickable history
🎨 Modern Dark Theme: Easy on the eyes with a sleek, professional interface
🖼️ Thumbnail Embedding: Automatically embeds video thumbnails in downloaded files
📱 Playlist Support: Download entire playlists with intelligent error handling
🔄 Live Progress Tracking: Real-time download progress with speed and ETA
💾 Automatic Fallback: Smart quality adjustment when requested resolution isn't available


Installation: Download Pre-built Executable (Recommended)

Go to the Releases page
Download the latest .exe file
Run the executable - no installation needed!

how to use?
Copy a YouTube URL - The app will automatically detect it
Select Quality - Choose from the dropdown menu (default:mp4 1080p)
Choose Save Location - Click "Browse" to select where files are saved
Click "Start Download" or use "Paste & Download" for instant downloading

Supported URLs

Single videos: https://www.youtube.com/watch?v=...
Short links: https://youtu.be/...
Playlists: https://www.youtube.com/playlist?list=...
YouTube Music: https://music.youtube.com/...

Quality Options
FormatDescriptionBest ForMP4 - 4K Best2160p video + audioHigh-end displays, archivingMP4 - 1080p Best1080p video + audioStandard high quality (default)MP4 - 720p Standard720p video + audioBalanced quality/sizeMP4 - 480p Basic480p video + audioQuick downloads, older devicesMP3 - 192k StandardAudio onlyMusic, podcasts
Features Explained
Intelligent Quality Fallback
If your requested quality isn't available, the app automatically downloads the best available quality and notifies you.
Download History
Click any item in the history panel to quickly reload that URL into the input field.
Playlist Handling
The app skips unavailable videos in playlists and continues downloading the rest, providing detailed logs.
Thumbnail Embedding
Downloaded videos include embedded thumbnails that appear in file explorers and media players.
Building from Source
To create your own executable:

buield using ?
python312
tkinter (GUI framework)
yt-dlp (download engine)
FFmpeg (video processing)

Platform Support:

✅ Windows 10/11
✅ Windows 7/8 (with limitations)
⚠️ macOS/Linux/android/IOS (comming soon)

Privacy & Legal

This tool is for personal use only
Respect copyright laws and content creators' rights
Only download content you have permission to download
The application does not collect or transmit any user data
Download history is stored locally on your device

Contributing
Contributions are welcome! Please feel free to submit a Pull Request here nioliocooperjdcorvayoubazizi@gmail.com 

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

Known Issues

Some age-restricted videos may require authentication
Very long playlist downloads may take considerable time 

Roadmap

 Batch URL downloads
 Custom output filename templates
 Subtitle download support
 Video preview before download
 Multi-language support

License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

yt-dlp - The powerful download engine
FFmpeg - Video processing backend
All contributors and users of this project

Support
If you encounter any issues or have questions:

Check the Issues page
Create a new issue with detailed information
Include the youtube_downloader_debug.log file if relevant


Disclaimer: This software is provided as-is for personal, educational purposes. Users are responsible for complying with YouTube's Terms of Service and applicable copyright laws.
⭐ If you find this project useful, please consider giving it a star!
