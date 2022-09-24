# RFID_ESP_VTS
RFID based entry and exist system for trucks at coal mines which creates record of entry and exit of drivers keep track of details of driver with the weight which they are carrying. Update it in database (xampp server).


This project uses UHF long range RFID of range upto 15 meters. Works on Weigand26 protocol. 
I used ESP-32 dev module for this project.
Pin no. 26 and 27 are used as D0 and D1 for weigand output. In weigand protocol we use 3 pin D0, D1 and ground. 
For database I hosted server locally with Xampp and used PHP and SQL for maintaing the database. 
