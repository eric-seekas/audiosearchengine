audiosearchengine
=================

Search for audio .wav files based on percent match in the audio file database

Place query wav file in the top level directory where interfacePython3Plus.py is stored.
Run search by running interfacePython3Plus.py. You can also add .wav files to the
db directory (database). 

Please note that the algorithm is designed for Python Version 3.X.X. (interfacePython3Plus.py).
Although, a separate interface file for Python Version 2.X.X. (interface.py) was made
it cannot be guaranteed that all of the modules and built-in functions compatible with Version 3.X.X
will behave exactly as intended in the older version of Python.

If possible, run interfacePython3Plus.py with python3 command.

Example:

.WAV Search Engine Version 1 (For Python Ver. 3+) 
Submit .wav file to search against database (Example: button.wav): button.wav
button.wav

**Higher number of partitions increases false positive rates, 
while lower number of partitions increases false negative rates

Set number of partitions of the query from 1 to 2862: 1000
Set number of samples of partitions from 1 to 1000 (Recommend < 50): 50
Scanning .wav file  0.00 %
Scanning .wav file  2.00 %
Scanning .wav file  4.00 %
Scanning .wav file  6.00 %
Scanning .wav file  8.00 %
Scanning .wav file  10.00 %
Scanning .wav file  12.00 %
Scanning .wav file  14.00 %
Scanning .wav file  16.00 %
Scanning .wav file  18.00 %
Scanning .wav file  20.00 %
Scanning .wav file  22.00 %
Scanning .wav file  24.00 %
Scanning .wav file  26.00 %
Scanning .wav file  28.00 %
Scanning .wav file  30.00 %
Scanning .wav file  32.00 %
Scanning .wav file  34.00 %
Scanning .wav file  36.00 %
Scanning .wav file  38.00 %
Scanning .wav file  40.00 %
Scanning .wav file  42.00 %
Scanning .wav file  44.00 %
Scanning .wav file  46.00 %
Scanning .wav file  48.00 %
Scanning .wav file  50.00 %
Scanning .wav file  52.00 %
Scanning .wav file  54.00 %
Scanning .wav file  56.00 %
Scanning .wav file  58.00 %
Scanning .wav file  60.00 %
Scanning .wav file  62.00 %
Scanning .wav file  64.00 %
Scanning .wav file  66.00 %
Scanning .wav file  68.00 %
Scanning .wav file  70.00 %
Scanning .wav file  72.00 %
Scanning .wav file  74.00 %
Scanning .wav file  76.00 %
Scanning .wav file  78.00 %
Scanning .wav file  80.00 %
Scanning .wav file  82.00 %
Scanning .wav file  84.00 %
Scanning .wav file  86.00 %
Scanning .wav file  88.00 %
Scanning .wav file  90.00 %
Scanning .wav file  92.00 %
Scanning .wav file  94.00 %
Scanning .wav file  96.00 %
Scanning .wav file  98.00 %
db/beep-03.wav
db/beep-06.wav
db/beep-07.wav
db/beep-08b.wav
db/beep-10.wav
db/button.wav
db/buttonframeshift.wav
db/buttonresampled.wav
db/clonebutton.wav
db/clonebutton_cut.wav
Number of Needles:  50
Search Result:
db/beep-10.wav :              2.00 % match
db/buttonframeshift.wav :     100.00 % match
db/beep-03.wav :              2.00 % match
db/button.wav :               100.00 % match
db/buttonresampled.wav :      100.00 % match
db/beep-06.wav :              2.00 % match
db/beep-08b.wav :             2.00 % match
db/beep-07.wav :              2.00 % match
db/clonebutton.wav :          100.00 % match
db/clonebutton_cut.wav :      98.00 % match
11.972685098648071 seconds