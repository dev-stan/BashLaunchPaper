## Create and run a Paper server with a simple script
### How does it work?
The script gets some input from the user specyfing the server folder `name`, amount of `ram` to be used, and the desired `port` to run the server on. It then downloads Paper with `curl`
and generates a `./start.sh` script which specifies the amount of ram to be used on startup. It also generates the `eula.txt` file agreing to the conditions and `server.properties` that has the user input port already set to it so the server is ready to go.


