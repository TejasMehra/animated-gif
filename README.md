Animated GIF Maker is a web-based tool built with Python and Streamlit that converts video files (e.g., MP4, MOV) into animated GIFs. Users can upload a video, adjust parameters like resolution, speed, duration, and frames per second, and then generate a downloadable GIF from the selected portion of the video.

![App Screenshot](https://raw.githubusercontent.com/TejasMehra/animated-gif/refs/heads/main/prototype.png)

Key Features:
- File Upload: Users can upload a video.
- Custom Settings: Sliders let users adjust video resolution, playback speed, and the range of video to convert.
- Preview: A single frame from the video is previewed.
- GIF Generation: The selected portion of the video is processed and exported as an animated GIF.
- Download: The generated GIF can be downloaded directly from the app.
The app uses moviepy for video processing and Pillow for image handling.