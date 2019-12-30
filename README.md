# JS Analyzer
This is a tool built by ComNets AD lab @ NYUAD to help in the classification of JavaScript. The tool allows the user to visualize the enabling and disabling of individual scripts.

# Chrome Driver Installation
You need to have the right version of chrome driver to install. You can refer to the following page for more details.
https://chromedriver.chromium.org/downloads/version-selection

Once you have the right chrome driver, you need to locate it in a location that is in your system path. You can refer to the following page for more details.
http://jonathansoma.com/lede/foundations-2017/classes/more-scraping/selenium/

# Connecting to the Proxy and installing certificate
Your WiFi should be connected to the proxy server. To do the required changes, you should do the following:
Go to your WiFi, open network preferences, choose proxies, and check the following:

Web Proxy (HTTP)
Secure Web Proxy (HTTPS)

for each of the checked options, you need to enter the following ip: 10.224.41.171 and then the port number (in the space after ":", which is: 8080

## Start JS Analyzer

    $ python3 analysisTool/analysis_tool.py

Enter a website into the window and click "Analyze page" to see how the page looks with all scripts removed. Click on a script button to display the content of the script and reload the page with that specific script enabled.
