FROM node:alpine
WORKDIR /usr/Q5/subscriber
COPY subscriber.js /usr/Q5/subscriber
RUN npm install mqtt
CMD ["node", "subscriber.js"]

# mosquitto_pub -t "test/sensor-data" -h localhost -p 6502 -f /home/diot/Desktop/220340126010/Q5/data.json
# This command will send the .json file to the subscriber
