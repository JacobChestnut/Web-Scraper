# Web-Scraper

This program will text a phone number (through [Twilio](https://www.twilio.com)) if a website that you have chosen to monitor has changed. All you need to do is enter the website URL, the number you want the text from, and the number you want the text to go to. This is done through scrapervariables.py.

Specific to this code, the program will scrape a weather report for the current weather, and send it to the user's phone number at 6am.

## To Begin
- You will need to import requests.
```
pip install requests
```
- You will also need a [Twilio](https://www.twilio.com) account.

## scrapervariables.py
You will need to create a file called "scrapervariables.py" with the following variables:
```
url = "THE WEBSITE YOU WANT TO MONITER"
account_sid = "YOUR ACCOUNT SID FROM TWILIO"
auth_token = "YOUR AUTH TOKEN FROM TWILIO"
twilio_phone_number = "+1THE NUMBER YOU WANT THE TEXT TO COME FROM (FROM TWILIO)"
my_phone_number = "+1THE NUMBER YOU WANT THE TEXT TO SEND TO (YOUR PHONE NUMBER)"
```
Don't forget the +1 before the phone numbers!

###### As a general courtesy, please respect a website's terms of use and don't overload their servers!

[This is the link to the site containing information about the program](https://jacobchestnut.github.io/Web-Scraper/)
