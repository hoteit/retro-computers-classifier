# retro_computers_dl_classifier

Retro computers classifier using Fast AI

While learning to use Fast AI code, I thought of testing a classifier for recognizing old school computers. Just for fun and learnig.

Tasks needed:

1. Preparing the Data:
-[x] build script to capture images from Google Images
-[x] get images for the computers
-[ ] clean the files
2. Get an existing pretrained model
3. Apply the model on the data and see the % accuracy

## Setup

- captured images from Bing using [bing scraper](https://github.com/ultralytics/google-images-download)
(note you need to download [google chrome driver](https://chromedriver.chromium.org/))

An example of calling the command `python D:\library\google-images-download\bing_scraper.py --url 'https://www.bing.com/images/search?q=vectrex' --limit 100 --download --chromedriver C:\Users\th_281295\Downloads\chromedriver.exe`

Note that I had to use Windows Powershell instead of Linux because it was not worth getting google chrome driver to work in my Windows Subsystem for Linux 2(WSL2)
