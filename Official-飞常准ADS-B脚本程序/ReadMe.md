Welcome to VariFlight ADSB Client setup
---------------------------------------

Setup VariFlight ADS-B Client...
You will first need a working version of any feeder before proceeding.
Example FlightAware or any pre-build ADS-B image already installed.
Else setup for VariFlight feeder will failed!
This setup script just borrow the existing feeder Dump1090 decoder to function.

  - Login as root.

  - Unzip the file into the root folder.

  - Type "chmod +x *.sh"

  - Type "bash setup.sh" Setup VariFlight ADS-B Client installer...

  - Select "0" for /bin/nano. 
  Select easiest editor item "2".

  - Ensure only one set of two lines cron job exist...
  Press "Control + O" to Write Out.
  Press "Control + X" to Exit.

  - Copy down the UUID code and 
   mailto:adsb@variflight.com for account activation
   go to http://flightadsb.variflight.com for registration.

  - Type "reboot" or wait 1 minutes to auto reboot.

  - For support email adsb@variflight.com

Note: - Once you have obtained the UUID code, please forward the UUID together
with your nearest airport Name / ICAO code to adsb@variflight.com
to bind into your variflight membership account.

Thank you.
VariFlight Team 

P.S. If you are using WiFi please modify "nano /root/get_message/get_ip.py"
Change the value to "eth0" to "wlan0" at the end of the script...
"eth=get_ip_address('eth0')"


Engineered by Rodney Yeo @ http://rodyeo@dyndns.org/
