# Legacy Devices
## Relay
This is the relay-based Legacy Devices client. You can use this on devices that can't use the API-based client, however this client does require some setup.

## How to set up
1. Download the `index.html` and `main.py` files.

2. Install Python 3.11 and the Python dependencies `flask`, `flask-restful`, and `websocket-client`.

3. Open the `main.py` file, and modify the `user`, `pswd`, and `hostip` variables to their respective values.

4. Run the `main.py` file.

5. Run an HTTP server, you can do this easily by running `python3 -m http.server`.

6. Open the `index.html` file, and modify the `ip` and `port` variables to their respective values.

7. Open the HTTP server in your device's web browser. The URL should look something like `http://192.168.1.71:8000/`.

## Checklist
This client is **36%** complete as per the Meower Everywhere Feature Checklist (not including non-feasible features)
- [x] - Viewing Posts
- [x] - Making Posts
- [ ] - Discord & Revower bridge support
- [ ] - Webhooks bridge support
- [ ] - Connecting to Meower via API
- [X] - Logging in with a username and password*
- [ ] - Displaying Images
- [X] - Connecting to Meower via websockets*
- [ ] - Editing Posts
- [ ] - Deleting Posts
- [ ] - Group Chats

`*` Works partially or with workaround

~~Item~~ | Feature is not feasible on this specific platform
