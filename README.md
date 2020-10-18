# auto-texter
Trick your significant others into thinking you wake up at 6:00am and have your life together


## Setup
1. Configure environment + install dependencies (if virtualenv isn't installed, install with `pip3 install virtualenv`)

       virtualenv env
       source env/bin/activate
       pip3 install -r requirements.txt
       
2. Follow the Twilio Quickstart guide to setup an account and project `https://www.twilio.com/docs/sms/quickstart/`

3. Clone this project and replace the keys in `.env-sample` with your Twilio keys and respective phone numbers + rename the file to `.env`

4. Follow `script_1.py` or `script_2.py` as per your needs (a fire as needed script vs. a permanent uptime script)
