# Mobile-Document-Scanner
## Technologies Used
- Optical Text Recognition
- Natural Language preprocessing
<p>***Make a file ocr.py in the project folder.***</p>

## Setup Virual Environment
<p><code> $ virtualenv venv --python=python3.6 </code></p>
<code> $ source venv/bin/activate </code>

## Install dependencies
- Pillow
<code> pip3 Install Pillow </code>
- Pytesseract
<code> pip3 Install pytesseract </code>
- OpenCV
<code> pip3 Install opencv-python </code>
- NLTK
<code> pip3 Install nltk </code>

## Run ocr.py
<code> python3 ocr.py --image images/story1.jpg > story.txt </code>

## story.txt
This file contains all the text from the image story1.jpg using ***OCR with pytesseract***.
<p>***Make a new file summarize.py***</p>

## summarize.py
In this file we used python's NLTK for removing stop_words, puctuations. And also word & sentence tokenizers from the NLTK library.   

## Run summarize.py
<code> python3 summarize.py story.txt > summary.txt </code>

## summary.txt
This file contains the ***summary*** of the the text file ***story.txt***.
