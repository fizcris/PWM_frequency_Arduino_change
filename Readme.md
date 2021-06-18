##  Change PWM frecuency ARDUINO UNO
### Function:  		setPwmFrequencyUNO(pin,divisor);
Description:

DO NOT MODIFY pin 6 is the one on which rely all time functions in Arduino: i.e., 
if you change the frequency of this pins, function like delay() or millis() 
will continue to work but at a different timescale (quicker or slower!!!)
 
 For pins 6 and 5:   (5 and 6 are together, can not modify individually,same timer)
 
     Divisor 	        Frequency
   	1 	 	62500 Hz
	2 	 	7812.5 Hz
	3 	 	976.5625 Hz  <--DEFAULT Diecimila bootloader
	4 	 	244.140625 Hz
	5 	 	61.03515625 Hz  
	

For pins 9, 10, 11 and 3: (9 & 10 and 11 & 3 are together, can not modify individually,same timer)
 

    Divisor 	 Frequency
	1 	 31372.55 Hz
	2	 3921.16  Hz
	3 	 979.527  Hz
	4 	 490.20   Hz   <--DEFAULT Diecimila bootloader
	5 	 244.882  Hz
	6	 122.55   Hz
	7	 30.610   Hz	

## Change PWM frecuency ARDUINO MEGA 2560
  
 

###	Function:     setPwmFrequencyMEGA2560(pin,divisior); 
This pins are together, can not modify frequency individually,same timmer):

- pin 13, 4
- pin 12, 11
- pin 10, 9
- pin 5, 3, 2
- pin 8, 7, 6
 
For pins 13,4 (DO NOT MODIFY pins 13 & 4 is the one on which rely 
all time functions in Arduino: i.e., if you change the frequency of this pins, 
function like delay() or millis() will continue to work but at a different timescale quicker or slower!))


     Divisor 	        Frequency

   	1 	 	62500 Hz
	2 	 	7812.5 Hz
	3 	 	976.5625 Hz  <--DEFAULT Diecimila bootloader
	4 	 	244.140625 Hz
	5 	 	61.03515625 Hz  
	
For pins 2 to 13 EXCEPT 13,4:
    Divisor 	 Frequency

	1 	 31372.55 Hz
	2	 3921.16  Hz
	3	 490.20    Hz   <--DEFAULT Diecimila bootloader
	4	 122.55    Hz
	5	 30.610    Hz	
