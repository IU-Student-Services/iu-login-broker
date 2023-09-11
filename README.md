# iu-login-broker
A simple broker for retrieving IU account information using OAuth

This does not store any data. It exposes a Websocket for creating login sessions with state (Discord ID for example) and getting back a URL to initiate OAuth login. Upon Login this will display a custom message provided by the WS client and send a message through the socket with IU Information.
