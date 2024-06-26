# youtube-art-track-builder

<img src="https://repository-images.githubusercontent.com/744533880/c41bb35d-6bbe-4881-9b43-83eacbcfab6a" width="500px">

[![CI](https://github.com/iamyukihiro/youtube-art-track-builder/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/iamyukihiro/youtube-art-track-builder/actions/workflows/ci.yml)

## Overview

YouTube Art Track Builder automates tedious video editing when posting original music to YouTube.

[YouTube Help - What is an Art Track?](https://support.google.com/youtube/answer/6007071?hl=en)

### Generates the following

- Image file
- Video file

### Please prepare the following

- Music file
- Album Cover file

## Output file

[![YouTube - Variations on Electronica for Today](https://img.youtube.com/vi/gUQ7W164I3Y/0.jpg)](https://www.youtube.com/watch?v=gUQ7W164I3Y)

## Requirement

- Docker Engine
- Docker Compose

## Usage

#### 1. Setup

Please, booting container.

`bin/compose`

Move your data into the `input/jacket.jpg` directory.

#### 2. Image generate

`bin/command/open-video-image`  
`bin/command/open-thumbnail`

Please display your browser in full screen.
Take a screenshot of the entire screen by pressing `Shift(↑) + Command + 3`.

#### 3. Video generate

Move your screenshot into the `input/*` directory.

`bin/command/generate`

## Special Thanks

I used the following article for CSS and ideas.
Thank you!

https://gist.github.com/adrienjoly/3290cba25c3350e264c0a43765f11e75
