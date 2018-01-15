# Image-Text-ForeignLanguage
Python Tesseract
================

Python-tesseract is an optical character recognition (OCR) tool for python.
That is, it will recognize and "read" the text embedded in images.

Python-tesseract is a wrapper for `Google's Tesseract-OCR Engine <https://github.com/tesseract-ocr/tesseract>`_. It is also useful as a
stand-alone invocation script to tesseract, as it can read all image types
supported by the Python Imaging Library, including jpeg, png, gif, bmp, tiff,
and others, whereas tesseract-ocr by default only supports tiff and bmp.
Additionally, if used as a script, Python-tesseract will print the recognized
text instead of writing it to a file.

Installs
--------

1. Install pytesseract : pip install pytesseract
2. pytesseract states that it requires Python Imaging Library (PIL) 
  pip install pillow
3. For Translation purpose:
  pip install googletrans
  
Functionalities
---------------

Declaring object class for Translator.

----- translator = Translator()

Calling a PIL function "image_to_string" that will convert text from image.

----- text = pytesseract.image_to_string(im)

This will translate the text to any user specific language.

----- translator.translate(text, dest=lang[lan])
