# CN_PropDelay

TRANSMISSION DELAY VERSUS PROPAGATION DELAY

Name: LakshmiChaganti
WIU Id: 921421942
Webpage URL:http://www.wiu.edu/users/lsc112/

Git URl: https://github.com/chagantila2/CN_PropDelay

•	Data is delivered to a network in the form of packets in computer networks, and this kind of data transport is known as packet switching.
•	Packet switching, also known as virtual circuit switching
•	There may be four delays in communication while transmitting data, the most prevalent of which being transmission and propagation delays.

Transmission delay:

•	The length of time it takes to put all of the packet's bits into the wire/connection medium is known as transmission delay. It is the delay induced by the link's data rate.
•	Store-and-forward delay and packetization delay are two terms that can be used to describe transmission delay.
•	The length of the packet determines the transmission latency. It is proportional to the number of bits sent and inversely proportional to the transmission rate.
•	 Data size / Band width = Transmission delay.

Propagation delay: 

•	 The time it takes for a signal to reach its destination is known as propagation delay.
•	 It refers to the time it takes for the signal's head to travel from the transmitter to the receiver.
•	 Wave propagation speed is inversely related to propagation delay and is directly proportional to distance.
•	Distance / transmission speed = D / S = propagation delay

Project Requirements:
The below figures illustrate how the length, Rate, Packet size, start and reset options has been implemented.
 
Length dropdown requirements:
 
Rate dropdown requirements: 

Packet Size dropdown requirements: 

Working: 

Requirement: 
The Project Required to implement a simulator which illustrates one of the most fundamental concepts in computer networking: transmission delay versus propagation delay.
Input:
User can set following
a)	the length of the link 
b)	the packet sizes 
c)	 the transmission speeds
d)	 the simulator shows the packet being sent from sender to receiver.
Result:
Input: 
Length:10KM
Rate: 512kbps
Packet Size: 100 bytes
Output
Time Taken : 7.007 ms

Testcase 1: 
With a length of 10km, a rate of 1Mbps, a packet size of 100 bytes, and a propagation delay of 2.8* 108 m/sec, the propagation delay is set at 2.8* 108 m/sec. We'll look at the red colored bar above the connection, which indicates packet transit from sender to recipient.:

Testcase-2:
With Length of 10km, Rate of 512Mbps, packet size of 100 byte and the propagation delay of 2.8* 10^8 m/sec which is the fixed value. we will check with the red colored bar over the link which is the indication of movement of packets from sender to receiver:

When all the properties are set the packet:


Testcase-3: 

With the distance of 1000km, a data rate of 512Mbps, a packet size of 100  kilobyte, and a propagation delay of 2.8* 108 m/sec, the propagation delay is set at 2.8* 108 m/sec. We'll look at the red colored bar above the connection, which indicates packet transit from sender to receiver:

When all the properties are set the packet:
 
 
How to Execute

Step-1: Executing the program:

tranPropDelay sourcepackage  com.propdelay.controller  propdelay.jsp (Right click)
 

Step-2: Need to set up the Tomcat server v9.0 before you start the execution.

 
Step-3: As soon as you follow the step-1 and run the program on server “Run on server” pops up and there “choose the existing server as Tomcat v9.0 server and click on Next tab at the bottom.



Step-4: After hitting the finish tab in step-4 the page gets redirected to local host with port address as 8080. Copy the url link from netbeans and follow the next step.
 

Step-5: Copy the link and paste it in your favorite browser


Step-6: You URL should contain:

  http://localhost:8080/TranPropDelay/frontEndDisplay/propDelay.jsp We can see the web page with project requirements where we can test the packet delays.






