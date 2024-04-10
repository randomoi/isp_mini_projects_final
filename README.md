
# Intelligent Signal Processing - Mini projects - Final

### Student: https://github.com/randomoi/

***

### Project Name: EX1 Final - Motion Detection

- Please use Jupyter Notebooks to run the project. 

### Project Name: EX2 Final - Rice, Huffman and FLAC

- Please use Jupyter Notebooks to run the project. 

### Project Name: EX3 Final - Video analysis using ffprob and conversion using ffmpeg

- Please use Jupyter Notebooks to run the project. 


## Installation of ffprobe and ffmpeg

I used HomeBrew to install ffprobe and ffmpeg, which was previously installed on my Mac computer (Ventura 13.5.2). I currently have Homebrew 4.1.10 version. The following instructions will show how to install ffprobe and ffmpeg on Mac and Jupytor Notebooks.

***

#### Installation using terminal on Mac

install HomeBrew:
	/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

install ffmpeg and ffprobe (one command):

	brew install ffmpeg

confirm installation:

	ffmpeg -version
	ffprobe -version

my installed versions:

	ffprobe version 6.0 
	ffmpeg version 6.0

***

#### Installation on Jupyter Notebooks:

I experienced issues with Jupyter Notebook when trying to import ffmpeg, but the following fixed the problem.

add path for Jupyter Notebooks to recognize ffmpeg"

	import os
	os.environ['PATH'] = '/usr/local/bin:' + os.environ['PATH']

checks path configuration

	import shutil
	shutil.which("ffmpeg")

check version

	!ffmpeg -version


