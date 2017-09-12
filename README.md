# nginx-cors

Takes the nginx image and adds CORS support to it.
The CORS configuration is in the cors_support file
To add additional headers modify the CORS configuration file

use docker to build and run a docker image
use this nginx image will allow javascript based api ajax calls

To build docker image
docker build -it <tag> . 
