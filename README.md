# image-to-text-to-audio-project
To covert text from an image to an audio file using python. 
REQIREMEMTS :
1. Python 3.x
2. Pillow library
3. pytesseract library
4. gtts library
5. tesseract-OCR

EXPLAINATION :
1. Image to Text -
   Use the Pillow library to open an image.
   Use pytesseract (Python wrapper for Tesseract OCR) to extract text from that image.
2. Text to Speech
   Use gTTS (Google Text-to-Speech) to convert the extracted text into speech.
   Save the speech as an MP3 file and play it using os.system().
