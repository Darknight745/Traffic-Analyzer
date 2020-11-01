# Traffic-Analyzer
Analyzes and visualizes the network traffic data coming to a server. 

### To run the server instance
``` sh
$ node app_new.js
$ lt --port 3000
```
The last line gets a public domain name for your server.

Paste the link generated in the **/Traffic-Generator/traffic-final.py** on **line 30**.

Make sure it is **http://...** instead of **https://...**

We are currently trying to automate this. 

Generate traffic using the above method or simply open the link in your browser.

When a certain number of packets are captured, a browser opens up and all the data can be visualized with the help of the graphs present there.

#### To Capture more packets

Change the -c option value to desired number on **line 26** in the file **/capNviz.py**
