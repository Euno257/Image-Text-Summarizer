# Image-Text-Summarizer
It mainly comes in use when the reader is reading Novels, Stories or anything which contains large set of paragraphs. The reader can take an image of the paragraph and input it to the model. And the model will result in a summary of that paragraph. Basically, the model makes reading easy and time saving for the readers. 
## Technologies Used
- Optical Text Recognition
- Natural Language preprocessing
#### Make a file ocr.py in the project folder.

## Setup Virual Environment
<p><code> $ virtualenv venv --python=python3.6 </code></p>
<code> $ source venv/bin/activate </code>

## Install dependencies
- Pillow
<code> pip3 install Pillow </code>
- Pytesseract
<code> pip3 install pytesseract </code>
- OpenCV
<code> pip3 install opencv-python </code>
- NLTK
<code> pip3 install nltk </code>

## Run ocr.py
<code> python3 ocr.py --image images/story1.jpg > story.txt </code>

## story.txt
This file contains all the text from the image story1.jpg using ***OCR with pytesseract***.
#### Make a new file summarize.py

## summarize.py
In this file we used python's NLTK for removing stop_words, puctuations. And also word & sentence tokenizers from the NLTK library.   

## Run summarize.py
<code> python3 summarize.py story.txt > summary.txt </code>

## summary.txt
This file contains the ***summary*** of the the text file ***story.txt***.
