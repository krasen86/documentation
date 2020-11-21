# Setup
Follow this steps to set up the project.
 
## Broker
- Install Mosquitto Ecliplse 
https://mosquitto.org/download/
- Configure the broker to accept websockets on port 1884.  
  Add the following lines to the mosquitto.conf file.
  ```
  port 1883
  listener 1884
  protocol websockets
  ```
 
## Client
- Follow the [instructions](https://git.chalmers.se/courses/dit355/2020/group-2/client/-/blob/master/README.md) to set up the vue client.
 
## Dentist register
- Clone the repository
- Start the dentist registry
    - navigate to dentistregistry/registry
    - run ```node index.js```
