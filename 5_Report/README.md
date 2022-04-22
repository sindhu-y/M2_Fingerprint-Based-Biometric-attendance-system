# overview of the project


# ABSTRACT


In industrial and domestic applications attendance registering is important at each and every moment. Many face a lot of problems due to lack of proper attendance monitoring system. In
this project we use Fingerprint Sensor (R305) which senses the Fingerprint of a particular person; a buzzer and Led gets activated whenever a person places his finger on the sensor. 
This  project has a wide application inschool, college, business organization, offices where marking of attendance is required accurately with time. By using the fingerprint sensor,
the system will become more secure for the users.Biometric student attendance system increases the efficiency of the process of taking student 2 attendance.It will also prevent proxy attendance, thus increasing the
reliability of attendance records.Proper attendance recording and management has become important in today’s world as attendance and achievement go hand in hand. Attendance is
one of the work ethics valued by employers. Most of the educational institutions and government organizations in developing countries still use paper based attendance method for
maintaining the attendance records. There is a need to replace these traditional methods of attendance recording with biometric attendance system. The unique nature of fingerprint
makes it ideal for use in attendance management systems. Besides being secure, Fingerprint based attendance system will also be environment friendly. Fingerprint matching is widely
used in forensics for a long time. It can also be used in applications such as identity management and access control. This review incorporates the problems of attendance systems
presently in use, working of a typical fingerprint based attendance system, study of different systems, their advantages, disadvantages and comparison based upon important parameters

# INTRODUCTION

In the World of Technology, Biometrics plays an effective role in identifying Human beings.Through this project, we will develop a unique system that can identify students for
attendance purpose using their fingerprints. In this project, we are going to design aFingerprint Sensor Based Biometric Attendance System using Atmega32.
Simply we will be interfacing fingerprint sensor with Atmega32 microcontroller, LCD Display & RTC Module to design the desired project. In this project, we used the fingerprint Module and Atmega32 to take and keep
attendance data and records.By using the fingerprint sensor, the system will become more secure for the users. A system that records the attendance making use of biometric scanners and stores them securelyover cloud in the form of Google Spreadsheet can help resolve issues. 
humans are more likely to trust machines over people, which is likely evident from us revealing our ATM pin to a machine so easily. Today, in the world where AI, Machine learning, Chat bots, Smart Speakers, Robots etc are actively progressing, this synergy between humans and robots is only set to increase. 
Today, from bridge toll collectors to check-out cashiers everything around us is being replaced by machines to get the work done easier and more efficient. To keep up with the phase, in this project we will build a Bio-metric Attendance system using AVR microcontrollers to replace the manual procedure of taking attendance.
This system will be more reliable and efficient since it would save time and avoid dodgers.

# PROBLEM STATEMENT

Attendance plays a major role in educational institutions. The most common means of taking attendance in the classroom is by calling out the roll numbers of students or asking the
students to manually sign the attendance sheet, which is passed around during the lecture.The process of manually taking and maintaining the attendance records becomes highly
cumbersome. Biometric systems have reached a sufficiently advanced stage wherein they can now be deployed in systems without hampering portability. With the recent development of
various cloud based computing and storage systems, data can be securely stored and retrieved whenever required. Primarily, fingerprints and iris images are considered to be the most
reliable for use in biometric systems.

# Required Components

Atmega32

Fingerprint module (r305) 

Push Button or membrane buttons 

LEDs

Resistors

Power 12v adaptor

Buzzer 

16x2 LCD

RTC Module (ds1307 or ds3231)

LM7805 

capacitor

Transistor 



# Working

Whenever user place his finger over fingerprint module then fingerprint module captures finger image,and search if any ID is associated with this finerprint 
in the system.if fingerprint ID is detected then LCD will show attendence registered and in the same time buzzer will beep once.Along with the fingerprint module, 
we have also used an RTC module for Time and date data. Time and date are running continuously in the system, so Microcontroller can take time and date whenever a 
true user places his finger over fingerprint sensor and then save them in the EEPROM at the allotted slot of memory.
User may download the attendance data by pressing and holding key 4. Connect supply to circuit and wait and after some time, LCD will show ‘Downloading....’. 
And user can see the attendance data over serial monitor, here in this code software UART is programmed at pin PD7-pin20 as Tx to send data to terminal. 
User also needs a TTL to USB converter to see the attendance data over serial terminal.
And if the user wants to delete all the data then he/she has to press and hold key 2 and then connect power and wait for some time. 
Now after some time LCD will show ‘Please wait…’ and then ‘Record Deleted successfully’. These two steps are not shown in demonstration video given in the end.



# Conclusion

The experimental model was made following the circuit diagram and the desired results were obtained. Every time someone places his finger on the sensor the sensor reads the data and
stores it in the cloud. Next time someone wants to check the fingerprint he/she places the finger on the sensor. The sensor reads the data and searches and cross-checks the data with
stored fingerprints. If it matches with any of them then it displays the username, date and time. If not then says fingerprint doesn’t match .That’s how the whole system works. 
