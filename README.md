# Image-Text-ForeignLanguage

This python script will read an image and extract the text from it. Its a image to text translation. After translation, we can convert the text to any foreign language.

I hope you all like it. :)


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


Languages 
---------


This is the list of languages it offers a user to read the text in:-

"Bulgarian":"bg"
 

"Bengali":"bn"
 

"Catalan":"ca"
 

"Chinese Simplified":"zh-CN"
 

"Chinese Traditional":"zh-TW"
 

"Croatian":"hr"
 

"Czech":"cs"
 

"Danish":"da"
 

"Dutch":"nl"
 

"English":"en"
 

"Estonian":"et"
 

"Filipino":"tl"
 

"Finnish":"fi"
 

"French":"fr"
 

"Galician":"gl"
 

"German":"de"
 

"Gujarati":"gu"
 

"Greek":"el"
 

"Hebrew":"iw"
 

"Hindi":"hi"
 

"Hungarian":"hu"
 

"Icelandic":"is"
 

"Indonesian":"id"
 

"Irish":"ga"
 

"Italian":"it"
 

"Japanese":"ja"
 

"Korean":"ko"
 

"Kannada":"kn"
 

"Latvian":"lv"
 

"Lithuanian":"lt"
 

"Macedonian":"mk"
 

"Malay":"ms"
 

"Maltese":"mt"
 

"Norwegian":"no"
 

"Persian":"fa"
 

"Polish":"pl"
 

"Portuguese":"pt"
 

"Romanian":"ro"
 

"Russian":"ru"
 

"Serbian":"sr"
 

"Slovak":"sk"
 

"Slovenian":"sl"
 

"Spanish":"es"
 

"Swahili":"sw"
 

"Swedish":"sv"
 

"Tamil":"ta"
 

"Telugu":"te"
 

"Thai":"th"
 

"Turkish":"tr"
 

"Ukrainian":"uk"
 

"Vietnamese":"vi"
 

"Welsh":"cy"
 

"Yiddish":"yi"
