bedside-monitor
===============
This is the official repository for the Enabling Engineers Bedside-Monitor at Northeastern University.

If you've never worked with arduino, you can get the IDE here:
http://arduino.cc/en/Main/Software

General information / Datasheets / etc.:
https://www.sparkfun.com/products/11446

Currently, the todo-list looks something like this:
1.) Write a capture executable that reads in arduino data and places it into a .slp file. The data will look like the following, repeated on each line:
TIME,XVAL,YVAL,ZVAL

2.) Take the .slp file and generate a graph in MATLAB to analyze the data.

3.) Write a arduino simulator, which can take a .slp file as input, and write the data to a fake serial port that it creates.

4.) Write the Final capture executable that reads in arduino data and interprets it accordingly
