# Traffic-Analyzer
Analyzes and visualizes the network traffic data coming to a server. 

### To run the server instance
``` sh
$ node app_new.js
$ lt --port 3000 > ./Traffic-Generator/link.txt
# The previous line gets a public domain name for your server.

# To view the link
$ cat ./Traffic-Generator/link.txt
```

### To Generate Traffic
``` sh
$ python3 ./Traffic-Generator/traffic-final.py

# Generate traffic using the above method or simply open the link in your browser.
```

When a certain number of packets are captured, a browser opens up and all the data can be visualized with the help of the graphs present there.

### Example graph

![Traffic Visualisation](https://github.com/Darknight745/Traffic-Analyzer/master/newplot.png?raw=true)

#### To Capture more packets

Change the **-c** option value to desired number on **line 26** in the file **/capNviz.py**
