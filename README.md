# ASD-B Receiver

This flight tracker is built with node-red. It takes SBS messages from dump1090 via
port 30003.

## Usage
<<<<<<< HEAD

Build a docker image that contains dashboard, worldmap, npm, and functionx packages.

`docker build -t adsb .`

Then run a container with the flows mapped into the container.

`docker run -it --name adsb -v $(pwd):/data -p 1880:1880 adsb`

Now you can connect to the running flow.

`http://localhost:1880/flights`
=======
`docker run -it -v $(pwd):/data -p 1880:1880 nodered/node-red:latest-minimal`

Connect to your dump1090 process by configuring the tcp node on the first flow.
>>>>>>> 42a4169580b3addc758c435c718fa83c836cbdf6
