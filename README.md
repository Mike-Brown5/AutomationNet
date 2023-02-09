An Automation Python Script that let configure multiple CISCO devices simultaneously by doing the following:

1-Validate the IP file: It takes the path to a file containing a list of IP addresses as input and verifies if the file exists and then It checks if the IP addresses in the file are valid .

2-Check reachability of IP addresses: It uses the ping command to check if the IP addresses are reachable.

3-Establishing the SSH connections: It takes the path to an authentication file containing a username and password and a commands file as input. It then establishes an SSH connection to each IP address in the IP file using the provided credentials and executes the commands in the commands file.

4-Execute the SSH connections to multiple IP addresses simultaneously using multi-threading.
