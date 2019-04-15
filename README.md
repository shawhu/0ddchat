# 0ddchat
A fully working chatroom implementation with encryption.

- the chatrom client is a web app. It can be run on Google Chrome, Safari, Android Google Chrome, iOS Safari, Opera and many more.
- ALL transmittions between the relay server and the clients are encrypted with dynamically changing key (based on AES)
- The relaying server won't have to relay any keys used to encrypt transmissions. So absolutely no worry about the middle-man attack during the key exchange.
- The relayed messages will be automatically deleted on the server if all members in the room have recieved the message.
- The server won't kept any message, the server only works in the RAM, it doesn't use Mysql or any other persistant storage.

