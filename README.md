# remote-information-stealer
The code will read the contents of the files in the home directory of the victim user and send it over to the attacker's machine by establishing a TCP connection over port 5555.

1. Compile the code at the victim's machine.
2. Start a Netcat listener on port 5555 in the attacker machine.
3. Run the compiled code in the victim's machine.
