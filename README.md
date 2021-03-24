# covid-19-vaccine-scrapper
Scrapes vaccinespotter.org using headless selenium and alarms you when a vaccine is found in your area.  Quit refreshing endlessly, let python do it for you in the background!

## Installation
Make sure to get [jupyter notebook](https://jupyter.org/install), easiest through [andaconda](https://docs.anaconda.com/anaconda/install/)


Use the package manager [pip](https://pip.pypa.io/en/stable/) to install selenium to scrape and playsound, PyObjC for sound.

```bash
pip install selenium
pip install playsound
pip install -U PyObjC
```

## Usage

Open Jupyter and find the directory of the .ipynb file.

```bash
jupyter notebook
```

Change [Vaccine Spotter URL](https://www.vaccinespotter.org/) with your desired area and run!  If you get an error with [chromedriver](https://chromedriver.chromium.org/) download correct version and replace it in the directory






