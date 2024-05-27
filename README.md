# Make sure you have go installed on your system
After cloning, then build the project using `go build .`

Then run it using `./tcp-chat`

Open a terminal and type in `telnet localhost 8888` to connet and start chatting.

# Commands

- `/nick <name>` - get a name, otherwise user will remain anonymous.
- `/join <name>` - join a room, if room does not exist, the new room will be created. User can only be in one room at the same time.
- `/rooms` - show list of available rooms to join
- `/msg <msg>` - broadcast message to everyone in a room
- `/quit` - disconnects from the chat server

# Reference Video

[packagemain #20: Building a TCP Chat in Go](https://youtu.be/Sphme0BqJiY)