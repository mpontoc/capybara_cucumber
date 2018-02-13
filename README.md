# capybara_cucumber
My first project

how I solved my problem with chromedriver on ubuntu 16.04
https://christopher.su/2015/selenium-chromedriver-ubuntu/

Install ChromeDriver:1

sudo apt-get install unzip

wget -N http://chromedriver.storage.googleapis.com/2.26/chromedriver_linux64.zip
unzip chromedriver_linux64.zip
chmod +x chromedriver

sudo mv -f chromedriver /usr/local/share/chromedriver
sudo ln -s /usr/local/share/chromedriver /usr/local/bin/chromedriver
sudo ln -s /usr/local/share/chromedriver /usr/bin/chromedriver

######################################################################################################################

commands to generations a execution report are:

cucumber --format html -o report.html
or can be too
cucumber --format html out=> report.html

#will generate a archive report.html on mainlyng folder of the project

Case you wanna to generate a report in other folder so you may write that

cucumber --formart html -o folder/report.html

:) see ya bye bye
