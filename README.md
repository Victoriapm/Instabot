# Instabot
Yet another Instagram bot with Instapy

## Tools
- Selenium + webdriver for Firefox
- Firefox
- Python
- [Instapy](https://instapy.org/)

## Instructions
- Install Selenium:  
`pip install selenium`

- Install geckodriver (webdriver for Firefox):  
 Download the latest version from their [official repository](https://github.com/mozilla/geckodriver/releases)  
 `tar -zxvf geckodriver-v0.27.0-linux64.tar.gz`  
 `sudo mv geckodriver /usr/local/bin`  
 `chmod +x geckodriver`

- Install Firefox:  
`sudo apt install firefox`

- Install & update Instapy:  
`pip install instapy`  
`pip install instapy -U`

- Modify Instapy to accept cookies:  
Lately, there's been a change on Instagram's login page, and calling the login function from instapy doesn't work anymore because the cookies are missing. 
[Here](https://github.com/timgrossmann/InstaPy/issues/5834) you can find a temporary solution. 
In case you use linux, you can locate the Python Instapy directory using the comand `find`. 


## More information
- Original post that I followed in [Real Python](https://realpython.com/instagram-bot-python-instapy/#how-to-automate-a-browser)
- [Instapy actions](https://instapy.org/actions)
