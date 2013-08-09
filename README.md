# A minimal Go TCP chat example

Run this like

	go run ./golang-chat.go

That will run a TCP chat server at localhost:6000.
You can connect to that chat server like

	telnet localhost 6000

And, of course, others can connect using your IP
address like

	telnet YOUR-IP-HERE 6000

assuming your firewall allows it.