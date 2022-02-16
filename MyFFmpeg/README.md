# MyFFmpeg

Some FFmpeg commands and solutions.

## FFmpeg commands

| Command | Description |
| :--- | :--- |
| ffmpeg -i \<input_file\> -f srt -i \<srt_file\> -c:v copy -c:a copy -c:s mov_text \<output_file\> | Embed SRT file into mp4 with ffmpeg |
| ffmpeg -ss \<00:00:00 (beginning time)\> -t \<00:00:30 (duration)\> -i \<input_file\> -c:v copy -c:a copy \<output_file\> | Cut the video from specified time to (specified time + specified duration) |

## Solutions 