# transcode-directory

A small bash script to find and transcode files into mp4 container inside a directory. The utility will find any file terminated with the extension provided and then converts them into a slightly compressed mp4 version. This tool was created to run asd a cronjob to periodically converts files from plex dvr service that are .ts files in lossless formast into a more space friendly format.

## Installation

To use this tool, git the project and then copy or create a symlonk into /usr/local/bin. I personnaly use this to install

```bash
git https://github.com/Darkfull-Dante/transcode-directory.git
cd transcode-directory
ln -s transcode-directory /usr/local/bin/transcode-directory
```

## Usage

```bash
transcode-directory <extension> /path/to/parent/directory
```

**Important** Note that the original file is deleted after the transcode is done