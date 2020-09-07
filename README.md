# Requirements
## Python 3
To check if it is installed:

`python3 --version`

## pip3
To check if it is installed:

`pip3`

Otherwise install them. The way depends on platform.

# Install dependecies
`$ pip3 install bs4`

`$ pip3 install python-dotenv`

# Usage

`$ python3 p.py`


## Hint
Run script in background:

`nohup python3 -u p.py &`

Check python processes:

`ps ax | grep p.py`


## Using Cron

Edit the cron tasks:

`crontab -e`

Run it every 15 minutes:

`*/15 * * * * cd /ABSOLUTE_PATH_TO_DIR/ && python3 p.py >> /ABSOLUTE_PATH_TO_DIR/log.txt`