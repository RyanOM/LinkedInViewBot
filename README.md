# LinkedInViewBot

This is a small LinkedIn crawler based on Selenium and BeautifulSoup4.
It's goal is to collect LinkedIn profil links on each page it visits.

To get started, make sure you have [pip](https://pip.pypa.io/en/stable/installing/ "Get pip") and [Firefox](https://www.mozilla.org/en-US/firefox/new/ "Get Firefox") installed on your machine:


    # First clone the repository
    git clone https://github.com/RyanOM/LinkedInViewBot.git

    # Go to the directory:
    cd LinkedInViewBot

    # Create a virtual environment and activate it
    virtualenv mylinkedinbot
    source mylinkedinbot/bin/activate
    
    # Install the requirements
    pip install -r requirements.txt

    # Finally done? Get the bot running with
    python main.py [linkedin email] [linkedin password]


To stop the bot, simply close the Firefox window or `CTRL+C´ in your terminal. 
