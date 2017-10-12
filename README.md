Setup
--------------
- `npm install`
- Plugin the OpenBCI V3 Dongle and turn on the Board
- Run python scripts from (https://github.com/OpenBCI/OpenBCI_Python):

`python user.py -p "<serial port>" --add udp_server 127.0.0.1 8888 --add print`

- Start UDP server `--> /start`
- Run `node socket_server.js`
- Visit [http://127.0.0.1:8880](http://127.0.0.1:8880) to see your brain waves

Optionally 
- Use `python udp_client.py --json` from the scripts folder to verify data is coming through
- Use `python socket_client.py` from the scripts folder to view the Web Socket data coming back into Python (requires socketio-client)

