### Screen
Left to Right when screen flipped over the reader and in install position with gamebox upright
* BLK   - GND                   - Backlight Cathode
* BLA   - 5V                    - Backlight Ano0de
* RST   - 5V                    - resetDisplay
* PSB   - GND                   - Activate SPI
* E     - GPIO14 (Cockle pin D5)- SPI Clock
* RW    - GPIO13 (Cockle pin D7)- SPI MOSI  
* RS    - GPIO15 (Cockle pin D8)- Chip select (?)
* V0    - 5V                    - LCD contrast
* VCC   - 5V                    - USB power VIN (not 3V3)
* GND   - 0V                    - Ground

### RFID Reader
* SDA   Cockle Pin D5 GPIO14 (shared with SPI Screen using jumper to a row on breadboard)
* SCK   Cockle Pin D3 GPIO0
* MOSI  Cockle Pin D4 GPIO2
* MISO  Cockle Pin D2 GPIO4
* GND   Ground
* RST   Cockle Pin D1 GPIO5
* 3V3   3V3

### Power Rails
Make a rail for the screen with 2 jumpers, VIN and GND to get 5V
Use 3V3 & GND between Cockle Pin D4 & D5
