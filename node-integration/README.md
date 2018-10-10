## Reading from serial port and plotting

Backend -- `serial-read-plot.js`
- Reads from USB
- Serves HTML to client

Frontend -- index.html
- Plots data live
- No history

Both the backend and frontend uses javascript. Additionally, one could save to file and read from file ([example](https://www.w3schools.com/nodejs/nodejs_filesystem.asp))

### To run:

- ```$ npm install ```
  - This installs dependencies defined in the package.json file.
  - Make sure node_modules folder installs
- ```$ node serial-read-plot.js```
  - This runs the server
- Navigate your browser to http://localhost:3000


### Notes:
- If serial port device is not connected. Comment out the serial port code and uncomment the test code.

### References
- [Node.js](https://nodejs.org/en/)
- [Socket.IO](https://socket.io/get-started/chat/)
- [CanvasJS](https://canvasjs.com/html5-javascript-dynamic-chart/)
- [Serialport](https://www.npmjs.com/package/serialport)
- [Express](https://expressjs.com/en/starter/installing.html)
