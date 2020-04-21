# [HTB] Vaccine_sql_injection

This script exploit the SQL injection in the CTF vaccine on HTB
This script sends an nc executable to the server and runs it to generate a reverse shell
You must start a web server to host the executable nc --> exemple : sudo python -m SimpleHTTPServer 80
And you must run a nc listener --> exemple: nc -lvp 4444
Then you can execute this script with python3
Note: The netcat executable hosted on your web server must be GNU netcat (and therefore must not be the netcat from OpenBSD)

 Demo on youtube: https://youtu.be/2k7IirmLlxs 
