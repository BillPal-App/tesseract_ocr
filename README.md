# Tesseract OCR for Flutter

Tesseract OCR 4.0 for flutter
This plugin is based on  <a href="https://github.com/tesseract-ocr/tesseract">Tesseract OCR 4</a>
This plugin uses <a href="https://github.com/adaptech-cz/Tesseract4Android/"> Tesseract4Android </a>  and <a href="https://github.com/SwiftyTesseract/SwiftyTesseract">SwiftyTesseract</a> credit goes to both.

## Getting Started

You must add trained data and trained data config file to your assets directory.
You can find additional language trained data files here <a href="https://github.com/tesseract-ocr/tessdata">Trained language files</a>

add tessdata folder under assets folder, add tess_data.config.json file under assets folder. 

Plugin assumes you have tessdata folder in your assets directory and defined in your pubspec.yaml 

Check the contents of example/assets folder and example/pubspec.yaml