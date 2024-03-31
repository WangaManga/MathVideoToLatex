# Ma.TeX: From Videos to LaTeX!

## Inspiration
Watching videos for note-taking and understanding takes a significant time in a student/researcher’s life.

## What it does
We present a simple real-time video transcribing application to summarize and generate LaTeX code for any formulae and equations mentioned in the video.

## How we built it
Introducing a pioneering approach using Google Gemini AI to analyze math videos and transcribe their content seamlessly into a single Latex document. This transformative process would help students get a clear understanding of the video while saving time in watching an entire video. Our model can also translate the prompt generated into the language of their choice. 

## Challenges we ran into
Integrating the python script 

## Accomplishments that we're proud of
Figuring out a way to automatically transcribe and summarize a video through Gemini API. Translating the text from one language to another.

## What we learned
OpenCV for computer vision, Gemini API for calling the summarizer model, Figma for interactive design.

## What's next for Wake The Beep Up
While this is just a way for us to put our step in the game, we have several ideas for the future to enhance our application:
1. Adding the option to generate Python, SQL, or Java codes about the topic being discussed in videos
2. Allowing for multimodal input such as audio recordings, handwritten notes
3. Making the application more inclusive and accessible by converting text to speech.

   
## Built With:
figma, opencv, python, gemini

<img src="https://github.com/chaa-san/Snooze-Cruise/blob/main/images/Home.png" width="350" height=auto>


## To run the python Code:
Install  & import the following python libraries: opencv-python, dlib, imutils, scipy

And execute the command from python code folder path:
python DrowsinessDetection.py
