# Researcher Discovery Platform :
## About :
It is a live scraping tool that scrapes data of active researchers from IIT, IIIT, NIT, CSIR in the provided field of research. It scrapes information like name, affiliation, education, publications, etc of researchers from the sources like `vidwan`, `google scholar`& from official institutional websites. It also allows downloading the data in pdf format.
## Dependencies :
This project uses following python module and libraries.(use `pip` to install) : 
* `Selenium`
* `Webdriver For Selenium` (Here we're using chromedrive version **98.xx.xx** according to our chrome version) 
* `html5lib`
* `bs4`
* `requests`

## Steps :
1. Install Python 3.10 from the given link `https://www.python.org/downloads/`
2. Install all the dependencies mentioned above using the command `pip install [MODULENAME] in your CMD`
3. Install the chromedriver for suitable version of installed chrome in the OS from the link: `https://chromedriver.chromium.org/downloads`
4. Place the chromedriver .exe file in the Researcher_Discovery/hexapod folder.
5. Use any python interpreter to run the code, here we are using **VS CODE**
6. Open the terminal in the product directory and run the command `python manage.py runserver`
7. Once your server is started go to your browser and enter the URL `http://127.0.0.1:8000/`
8. Test the product.
