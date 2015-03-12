# Blockly

Google's Blockly is a web-based, visual programming editor.  Users can drag
blocks together to build programs.  All code is free and open source.

**The project page is https://developers.google.com/blockly/**

![](https://developers.google.com/blockly/sample.png)

This demo shows a pre-runtime configuration of the device blocks. demo.js reads all useful json device information from the server and writes a devices.js file under the folder /blocks. The toolbox of blockly (namely which blocks are to be shown on the left side of the page) at the moment won't be dynamically updated until the <xml> part of demo.html is manually updated.(i.e. one has to manually fill in the new device names under appropriate categories.)

To run the demo one must change the server address (apiUrl) in demo.js, then run **node demo.js** in command and then open up **http://localhost:8080/** in web browser.
