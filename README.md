# Assignment2
This is Assignment2 submission in Unix class
Name : Do Tran Gia Hung
Student ID : s3614721
Repository name : s3614721/Assigment2

Source : https://github.com/s3614721/Assignment2


Instruction for LEDs configureation

1. To start the program you need to enter the Terminal and enter program directory.

2. Type ./leds.sh to start the program

3. The screen will display :

	Please select an led to configure :  

	input2::capslock
	input2::compose
	input2::kana
	input2::numlock
	input2::scrolllock
	led0
	led1
	quit

	Warning : kana and compose are not available
	Please type the exact name on the list to choose the leds (e.g: input2::capslock  ) : 

4. Enter the exact name of a led (Since we can not print simpler names, so we have to require users to enter the exact name of led and input )

5. After enter the correct name of a led the terminal will display :

	Capslock

	What would you like to do with this led ?
	1. on
	2. off
	3. associate with system event
	4. associate with the performance of a process
	5. stop association with a process’ performance 
	6. quit
	Please enter choice from 1-6

5.1 and 5.2. This step is simple. We just need to enter 1 or 2 to turn a led on or off

5.3.1 Enter 3 and the terminal will display the list events we can use on a led we chose

	[none]
	rc-feedback
	kbd-scrolllock
	kbd-numlock
	kbd-capslock
	kbd-kanalock
	kbd-shiftlock
	....
	panic
	mmc1
	mmc0
	rfkill-any
	rfkill0
	rfkill1

	Please type the name of event correctly : 
	
5.3.2 Enter the correct of event (e.g: heartbeat) and the program will exit automatically 
	
6. Check the LEDs you just config.
