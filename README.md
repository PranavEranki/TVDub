# AnimeDub
Automated true-to-time language dubbing for TV shows with Google Cloud Platform speech to text, text to speech, and translation.

# What it does
This application takes in an mp4 (preferably a TV show), locates the audio in the mp4 and converts the source language to another language using text-to-speech; effectively dubbing the media in another language.

# How I built it
To build this I made use of google-cloud text to speech, translate, speech to text and python. I use approximation algorithms to define the location of each sentence said in the audio files and using this location I know where I can put the text-to-speech version of those sentences. Thanks to the great open source software of pydub and moviepy, I had awesome tools to edit audio files and video files.
