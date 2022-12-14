## IPV4Check - An NGINX webserver for reporting back your public IP


# Build
docker build -t ipv4check .


# Start
 docker run -p 80:80 -ti ipv4check


# Examples
http://ipv4check/?format=json

{"ip":"12.34.56.78"}


http://ipv4check

12.34.56.78
