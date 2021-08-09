# PersonalPVT

PersonalPVT is a Web application that supports Psychomotor Vigilance Task (PVT) testing. This is a kind of
test that is widely used by psychologists for quantifying sleepiness. When we are tired, we will nod off
 for short periods (scientists call it "micro-sleep"). This test is designed to catch those moments if
they are occurring. They will manifest as a slowing of reflexes.

Usually, testers in studies will have to take a ten-minute test as many as 6 times a day. But I think you can still get interesting
data even if you only take the test once or twice a day.

The application is available at https://dominiccanare.com/PersonalPVT

## Running locally
This needs to be hosted on a web server. If you want to run it locally, this can be done easily with [Python](https://www.python.org/) installed. Here are some instructions for Windows users:
* Open the `PersonalPVT` folder in Windows Explorer
* Replace the contents of the location bar with `cmd` and hit `Enter` (this will open a command prompt in this folder)
* Type `python -m http.server` and hit `Enter` (this will start the web server)
* Point your web-browser to [http://localhost:8000/](http://localhost:8000/)

## Features

 * Take anonymous PVT tests.
 * View test results graphed, alongside relevant statistics.
 * Save results to your browser and analyze trends over time.
 * Export all result data to CSV for your own records and analysis.

## Fork modifications
* Displays a looped video in the background of the trials
* Hides the timer value and displays a red-dot only
* TODO: log too-early responses
