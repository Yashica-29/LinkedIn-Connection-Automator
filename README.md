# LinkedIn-Connection-Automator

## Project Overview

The LinkedIn Automation Project is designed to automate the process of sending connection requests on LinkedIn. This project utilizes Selenium and the undetected-chromedriver library to handle the web interactions and manage LinkedIn's login process. The main goal is to streamline and simplify the process of expanding your LinkedIn network by automatically sending connection requests to potential contacts.

## Key Features

•	Automated Login: The project handles the login process to LinkedIn using pre-saved cookies, eliminating the need for manual login every time.

•	Connection Requests: Automatically sends connection requests to a list of specified LinkedIn profiles.

•	Cookie Management: Saves and loads LinkedIn session cookies to maintain login sessions.


## Prerequisites

•	Python 3.x installed on your machine

•	Google Chrome browser installed

•	ChromeDriver compatible with your Chrome browser version

•	Required Python libraries


## Usage

### Step 1: Manual Login and Save Cookies

1. Run the script to log in manually and save cookies.

2. Follow the on-screen instructions to log in to LinkedIn manually:
•	The browser will open and navigate to the LinkedIn login page.
•	Log in with your credentials within the given time frame.
•	The cookies will be saved automatically to a file named `linkedin_cookies.pkl`.


### Step 2: Automated Connection Requests

1. Prepare a list of LinkedIn profile URLs.

2. Run the script to send connection requests.

3. The script will load the saved cookies and automatically send connection requests to the profiles listed in `profiles.txt`.






https://github.com/Yashica-29/LinkedIn-Connection-Automator/assets/98029814/21971b37-bed7-40a2-b39c-013c0be8fbe8


