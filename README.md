# AI Short Video Creator - AutoCaption
Tool to automatically create short clips with a baground video and AI-generated captions.
Can be used for YouTube Shorts, TikTok, Instagram Reels, Snapchat Spotlight.

**No API keys** are required, the videos are processed locally on your computer.


## Table of Contents
- [Example](#example-output)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Attributions](ATTRIBUTIONS.md)

## Example Output

<img src="https://github.com/user-attachments/assets/0a59928f-fe80-4da9-946d-06a0ec6d1660" width="200" title="Example Output - Screenshot 2"/>

## Requirements
- Python >=3.7 - [Download Here](https://www.python.org/downloads)
- FFmpeg - [Download Here](https://ffmpeg.org/download.html)
- Git - [Download Here](https://git-scm.com/downloads)
- Git LFS - [Download Here](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage)


## Installation
1. Clone the repository:
```bash
 git clone https://github.com/sw-aka/Short-Video-Creator.git
```

2. Install dependencies:
```bash
 pip install -r requirements.txt
 ```
3. download pytorch_model.bin and copy to whisper-small.en/
```
https://huggingface.co/openai/whisper-small.en/tree/main
```

## Usage
1. Move MP4 main videos into ```INPUT_VIDEOS```
2. Move MP4 background videos into ```BACKGROUND_VIDEOS```
3. Run ```main.py```:
 ```bash
 python main.py
 ```
4. The editted videos are saved in ```OUTPUT_VIDEOS```

### Optional
You can edit the settings in ```config.py```.


