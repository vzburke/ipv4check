# IPV4Check - Webserver for reporting back ipv4 public IP address in various formats


## Build
``` docker build -t ipv4check . ```


## Start
``` docker run -p 80:80 -ti ipv4check ```


## Examples

#### Plain Text:
http://ipv4check/


    12.34.56.78
____


#### JSON:
http://ipv4check/?format=json

    {"ip":"12.34.56.78"}
____


#### XML:
http://ipv4check/?format=xml

    <?xml version="1.0" encoding="UTF-8" ?>
    <ip>12.34.56.78</ip>

___


#### YAML:
http://ipv4check/?format=yaml

    ---
    ip: 12.34.56.78
____

