# TesseractOCR-and-WorldList-Generator-using-PYOCR
This tutorial will guide you throught the installation process of TesseractOCR 3.04.01 with automatically installation 
of Leptonica1.73. Alongside this installation of PYOCR and extracting the wordlist and also how to get bounding box 
using tesseractOCR. 
## Installation of TesseractOCR in Ubuntu
### Installing Depedencies
To run tesseract fine few of the dependencies are necessary which can be installing by simply using following commands.
```
$ sudo apt-get install libpng-dev libjpeg-dev libtiff-dev zlib1g-dev
$ sudo apt-get install gcc g++
$ sudo apt-get install autoconf automake libtool checkinstall
```
### Installing TesseractOCR
To install the tesseractOCR simply write the following command
```
$ sudo apt-get install tesseract-ocr
```
Initially it will come with the -eng language. There 100's of languages available. To download any specific lanaguage
you can use the following template
```
$ sudo apt-get install tesseract-ocr-[lang]
```
for example
```
sudo apt-get install tesseract-ocr-fra
```
or simply download all the langaues pack available by using the command
```
$ sudo apt-get install tesseract-ocr-all
```