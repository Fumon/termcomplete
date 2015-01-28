#Termcomplete

A simple script for alerting your phone when a long terminal task is done (like compling the linux kernel).

##Installation

Put `termcomplete` somewhere on your PATH.

##Configuration

Create a file ~/.termcomplete.

Place in it an application key and your user key from Pushover.

    APP_TOKEN = "apptoken"
    USER_KEY = "userkey"

##Usage

Run your long running command and put termcomplete on the end:

   $ sleep 5; termcomplete
   
Once your command finishes, it will get pinged.
