# Crypto Market Session Indicator

Easily track the opening and closing levels of crypto market sessions on Trading View. 

Crypto Market Session Analyzer is an easy-to-use yet powerful analysis tool that helps the trader visualize and analyze price movements over three different trading sessions:

1) European Session
2) US session
3) Asian session

Automatically tracks the corresponding levels for each market session.

This indicator can be used on all timeframes equal to or less than 15 minutes.

Although this is a simple indicator to use, some care must be taken when using it. The trader must be careful to set the correct times for each session according to his UTC timezone. By default the indicator uses UTC. If your console is set to UTC + 2 for example, you will need to take this into account and align the times correctly. You can adjust the time for each session from the user interface. Following the example, if the opening of the UE session is set to 9 and UTC of your console is set to UTC + 2, the script will proceed to create the level at opening time 11.

# HOW IT WORK

The indicator automatically draws a horizontal line at the open and a horizontal line at the close of each session. The indicator clears past support and resistance every 24 hours to provide a clean and easy-to-read chart, updating new levels session after session.

Blue indicates the EU session.
Orange indicates the US session.
Purple indicates the Asian session.

![Schermata 2022-05-08 alle 21 24 54](https://user-images.githubusercontent.com/100917872/167312415-7f8ac73e-7cd7-40d9-b92e-a26d4b7faae5.png)
