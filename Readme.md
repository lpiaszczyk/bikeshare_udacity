The solution makes use of external library, please remembr to run
pip install -r requrements.txt
before run.

Run with:
python bikeshare.py

Additional note:
I've added option to analyse data from all cities. As some data for Washington is missing, statistics may not be accurate - I've mentioned that in message presented to user.
Additionally, as Trip Duration data is stored as float, I've decided to convert it to int - I'm aware of possible precision lost, but we need data to be of the same type.