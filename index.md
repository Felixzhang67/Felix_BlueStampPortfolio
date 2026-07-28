# Bluestamp Robot Project
Let's say you want to buy and play with a robot or a mini tank. However, you find out that either they are sold out or out of your price range and there is no way you can get one from any store or online ordering site. This project that is shown contains all the necessary components and parts that will make your day and let you have all the fun and adventure you want.


| **Engineer** | **School** | **Area of Interest** | **Grade** |
| Felix Z. | Army and Navy Academy| Mechanical engineering or Law | Incoming Senior |

![Headstone Image](07568605-6E82-4C82-BC6C-A210968218B9_1_105_c.jpeg)


# Third Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/sAvNpXg4cZk?si=KJcDt0KYNVU-8vxa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Introduction: This is my third milestone. I was able to control my robot successfully using the IR (Infared) remote and also updated my code in order to accomplish the connection between the Bluetooth module on the mini tank project to my IR remote.

Successes: The mini tank robot was able to move by the IR remote, which was able to connect with the bluetooth module that is on the project. This connection along with the newly updated code allowed my IR remote to move around the robot without just it following only the uploaded base code.

Challenges: A lot of my challenges that I faced were mostly connecting the IR remote to my project. The code for the IR remote that I put in had many complication errors like a line of code was not declared or the lines of code were not closed. Another challenge was trying out the controller. It was difficult to control it at first since there were many connection problems/errors and even when it had a good connection, when pressing the direction buttons it was still difficult to control where I want my project to go.

Future Goals: My last goal is to work on a modification on my mini tank project. The modification is that instead of using my IR Remote, I will instead use my phone as the controller instead. This way, I don't have to use my IR remote, which is a bit difficult to use, and can instead use my phone as an easier alternative controller.

Conclusion: My biggest challenges at BSE were mostly the coding part of BSE. It gave me the biggest challenge since I had to fix through many coding errors and even also building issues like loose screws, figuring out the placement of the wires, and building the bottom half of the mini tank robot. I learned many important topics at BSE but the most important ones I think I learned here is mechanical engineering (how to build stuff) and a introduction and depth into the world of coding. In the future after BSE, I hope I can learn more about the field of engineering, like how other parts work and learn more about how coding works for different things and dive more into the world of coding.




# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/qdJSDtxgtMA?si=9tu74roJGp_QFAGp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Introduction: This is my second milestone. For my second milestone, I worked on my basic movement code for my mini tank project which was making the tracks move forwards, backwards, and also to turn around and move left and right

Successes: The code was able to successfully upload and run as expected. The mini tank robot was also able to read the programming and follow the coding instructions to move forwards and backwards

Challenges: Some challenges I faced were mostly Complication errors and uploading issues. For instance, some of the errors I recieved were mostly brackets that were missing from the code or an extra copy of a code that is not supposed to be there. Another error I faced was also not declaring a line of code that was not previously declared. I also did experience some uploading issues. For example, when uploading my finished code it was not able to upload and the issue was the microcontroller was heating up a little bit.

Future Goals: In the next week, I will work on putting other important lines of code into my Arduino IDE and my bluetooth module code so I could control my project with the IR sensor remote. This will also be my 3rd mileston and if time allows I will also work on modifications.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZyAID4YIRaw?si=O3ZKyHvGhi6gX8Qo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Introduction: This is my first milestone for my mini tank project, which is building each part of the project like the tracks, main body, wiring, and main board.
 
Successes: I was able to successfully finish building my project. I was able to screw together everything in place and was able to catch any building errors like loose screws and wrong placements of nuts and bolts.

Challenges: Some challenges I faced is building the bottom half of the robot which are the tracks. I struggled how to put some of the pieces together, like putting the tracks around the gear and screwing in the bolts to put together the two tracks because of the placement and size. Another challenge was the placement of the wires, which was confusing since there were a bunch of them here and there and it was difficult following which wire is correctly supposed to go to there.
 
Future Goals: In my future milestones, I am going to take on the coding for my main project and work on it until it can run properly and upload to my project, which will hopefully be able to work as intended.


# Starter Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/8j-ba-zkg5s?si=kflLVxAjFd3qh76g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


Hi, my name is Felix Zhang. My starter project is the Mini Retro Arcade Game. How it works is you press the red button to turn it on. The blue buttons on the bottom left corner are the up, down, left, and right directions. The green and yellow buttons are there to help with other stuff like pausing and etc. When you turn it on, there are different versions of games similar to tetris that you can play. Some technical challenges I faced were soldering since it was my first time doing it. I was able to figure it out and finish it. 

<!--

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

-->!

# Code

 keyestudio Robot Car v2.0
 lesson 14.2
 bluetooth car
 http://www.keyestudio.com
*/

//Array, used to store the data of pattern, can be calculated by yourself or obtained from the modulus tool
unsigned char start01[] = {0x01,0x02,0x04,0x08,0x10,0x20,0x40,0x80,0x80,0x40,0x20,0x10,0x08,0x04,0x02,0x01};
unsigned char front[] = {0x00,0x00,0x00,0x00,0x00,0x24,0x12,0x09,0x12,0x24,0x00,0x00,0x00,0x00,0x00,0x00};
unsigned char back[] = {0x00,0x00,0x00,0x00,0x00,0x24,0x48,0x90,0x48,0x24,0x00,0x00,0x00,0x00,0x00,0x00};
unsigned char left[] = {0x00,0x00,0x00,0x00,0x00,0x00,0x44,0x28,0x10,0x44,0x28,0x10,0x44,0x28,0x10,0x00};
unsigned char right[] = {0x00,0x10,0x28,0x44,0x10,0x28,0x44,0x10,0x28,0x44,0x00,0x00,0x00,0x00,0x00,0x00};
unsigned char STOP01[] = {0x2E,0x2A,0x3A,0x00,0x02,0x3E,0x02,0x00,0x3E,0x22,0x3E,0x00,0x3E,0x0A,0x0E,0x00};
unsigned char clear[] = {0x00,0x00,0x00,0x00,0x00,0x00,0x00,0x00,0x00,0x00,0x00,0x00,0x00,0x00,0x00,0x00};
#define SCL_Pin  A5  //Set clock pin to A5
#define SDA_Pin  A4  //Set data pin to A4

// L9110 Motor Driver Pins
#define A_1A 13  // Motor A - Pin 1 (Not PWM)
#define A_1B 12  // Motor A - Pin 2 (Not PWM)
#define B_1A 11  // Motor B - Pin 1 (PWM Capable)
#define B_1B 3   // Motor B - Pin 2 (PWM Capable)

char bluetooth_val; //save the value of Bluetooth reception

/*************the function to run motor**************/
void Car_front()
{
   digitalWrite(A_1A, HIGH);
  digitalWrite(A_1B, LOW);
 
  analogWrite(B_1A, 255); // Max speed to match Motor A
  analogWrite(B_1B, 0);
}
void Car_back()
{
   digitalWrite(A_1A, LOW);
  digitalWrite(A_1B, HIGH);
 
  analogWrite(B_1A, 0);
  analogWrite(B_1B, 255);
}
void Car_left()
{
    digitalWrite(A_1A, HIGH);
  digitalWrite(A_1B, LOW);
 
  analogWrite(B_1A, 0);
  analogWrite(B_1B, 255);
}
void Car_right()
{
    digitalWrite(A_1A, LOW);
  digitalWrite(A_1B, HIGH);
 
  analogWrite(B_1A, 255);
  analogWrite(B_1B, 0);
}
void Car_Stop()
{
digitalWrite(A_1A, LOW);
  digitalWrite(A_1B, LOW);
 
  analogWrite(B_1A, 0);
  analogWrite(B_1B, 0);
}

// Gentle turning (T_left / T_right) works best with speed control.
// Since pins 12/13 can't do speed control, we'll pivot on one wheel instead.
void Car_T_left()
{
  // Motor A forward, Motor B stopped
  digitalWrite(A_1A, HIGH);
  digitalWrite(A_1B, LOW);
 
  analogWrite(B_1A, 0);
  analogWrite(B_1B, 0);
}

void Car_T_right()
{
  // Motor A stopped, Motor B forward
  digitalWrite(A_1A, LOW);
  digitalWrite(A_1B, LOW);
 
  analogWrite(B_1A, 255);
  analogWrite(B_1B, 0);
}
 //****************************************************************


void setup(){
  Serial.begin(9600);
  
  pinMode(SCL_Pin,OUTPUT);
  pinMode(SDA_Pin,OUTPUT);
  matrix_display(clear);    //Clear the display
  matrix_display(start01);  //display start pattern

  // Set L9110 pins to outputs
  pinMode(A_1A, OUTPUT);
  pinMode(A_1B, OUTPUT);
  pinMode(B_1A, OUTPUT);
  pinMode(B_1B, OUTPUT);
}

void loop(){
  if (Serial.available())
  {
    bluetooth_val = Serial.read();
    Serial.println(bluetooth_val);
  }
  switch (bluetooth_val) 
  {
     case 'F':  //forward command
        Car_front();
        matrix_display(front);  // show forward design
        break;
     case 'B':  //Back command
        Car_back();
        matrix_display(back);  //show back pattern
        break;
     case 'L':  // left-turning instruction
        Car_left();
        matrix_display(left);  //show “left-turning” sign 
        break;
     case 'R':  //right-turning instruction
        Car_right();
        matrix_display(right);  //display right-turning sign
       break;
     case 'S':  //stop command
        Car_Stop();
        matrix_display(STOP01);  //show stop picture
        break;
  }
}

/**************The function of dot matrix****************/
//this function is used for dot matrix display
void matrix_display(unsigned char matrix_value[])
{
  IIC_start();
  IIC_send(0xc0);  //Choose address
  
  for(int i = 0;i < 16;i++) //pattern data has 16 bits
  {
     IIC_send(matrix_value[i]); //data to convey patterns
  }
  IIC_end();   //end to convey data pattern
  
  IIC_start();
  IIC_send(0x8A);  //display control, set pulse width to 4/16
  IIC_end();
}
//The condition starting to transmit data
void IIC_start()
{
  digitalWrite(SCL_Pin,HIGH);
  delayMicroseconds(3);
  digitalWrite(SDA_Pin,HIGH);
  delayMicroseconds(3);
  digitalWrite(SDA_Pin,LOW);
  delayMicroseconds(3);
}
//transmit data
void IIC_send(unsigned char send_data)
{
  for(char i = 0;i < 8;i++)  //Each byte has 8 bits
  {
      digitalWrite(SCL_Pin,LOW);  //pull down clock pin SCL Pin to change the signals of SDA      
      delayMicroseconds(3);
      if(send_data & 0x01)  //set high and low level of SDA_Pin according to 1 or 0 of every bit
      {
        digitalWrite(SDA_Pin,HIGH);
      }
      else
      {
        digitalWrite(SDA_Pin,LOW);
      }
      delayMicroseconds(3);
      digitalWrite(SCL_Pin,HIGH); //pull up clock pin SCL_Pin to stop transmitting data
      delayMicroseconds(3);
      send_data = send_data >> 1;  // Detect bit by bit, so move the data right by one
  }
}
//The sign that data transmission ends
void IIC_end()
{
  digitalWrite(SCL_Pin,LOW);
  delayMicroseconds(3);
  digitalWrite(SDA_Pin,LOW);
  delayMicroseconds(3);
  digitalWrite(SCL_Pin,HIGH);
  delayMicroseconds(3);
  digitalWrite(SDA_Pin,HIGH);
  delayMicroseconds(3);
}



# Bill of Materials 

| **Part** | **Note** | **Price** | **Link** |
| Keyestudio V4.0 Development Board | the brain for my project and is used to read info from inputs and control outputs| $9.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/KEYESTUDIO-Development-Board-ATmega328P-Arduino/dp/B08H1RB61B)"> Link </a> |
| Tracks and gears | Used for my Mini Tank project to move around| N/A | <a href="N/A"> Link </a> |
| 2.0*40mm Screwdrivers | Used to screw the screws in| $10.30| <a href="(https://www.amazon.com/Wera-05117993001-Kraftform-Electronics-Screwdriver/dp/B003ES5LXG/ref=sr_1_10?dib=eyJ2IjoiMSJ9.M3kTZ0cjqcGZU56GhY8kLT5sXT3w370g8r0qox4-Hw0Rmxi8QkUowFnxsdjay8gObMsOWrB4pXtdPaQANWv90wNTufMOWeC1UgmZXWQzWmN85yb_PtKAM0VLyHH9-SMIH9B0zGucW1RVbssVKtMk998pNBD3HBOpMUFZN_8HoILHbYRM-vy2zta1MxMnA42LOParGTsoj_C5riU4MsvT6-Nd6ZyxYz2EguESBc1lpZzHOrynZwqIK33sQB7oB7Q_UxFHXPBywFqH8Zdj9SgYwdlW2p3FZRG58Px3y3LcYUs.j8-ef83Ri20e5YS-xNq6PiLjlepOOZvt7kDO_MNJrL8&dib_tag=se&keywords=Screwdriver%2Bprecision%2Bslotted%2B2%2B0x40mm%2BNEO&qid=1783011154&sr=8-10&th=1)"> Link </a> |
| Accessories Box | Has some of the important stuff for my project| NA | <a href="N/A"> Link </a> |
| Sensor Shield V5| Used for my project to plug in the sensors| NA | <a href="(https://www.newegg.com/p/1W7-00V1-00K00?item=9SIC12YKPJ0151&utm_source=google&utm_medium=organic+shopping&utm_campaign=knc-googleadwords-_-cables%20-%20internal%20power%20cables-_-aomoproing-_-9SIC12YKPJ0151&source=region&negg_topt=0&srsltid=AfmBOooFZkmp2wMC6Xg-YXBzT0AWsrvbHt7-IBNcqOsxfYOOU4ADeg6ISDM)"> Link </a> |
| Battery Holder | used to hold the batteries to power my project| NA | <a href="N/A"> Link </a> |
| motor shield | used for my project to handle speed, direction, and power and helps microcontroller| $28.40 | <a href="(https://store-usa.arduino.cc/products/arduino-motor-shield-rev3)"> Link </a> |
| HC-SRO4 sensor | used for my project to detect obstacles when one is too close| $5.25 | <a href="(https://store-usa.arduino.cc/products/arduino-motor-shield-rev3)"> Link </a> |
| Keyestudio Photoresistors | used for my project as a sensor when detecting the intensity of the light| $3.80 | <a href="(https://www.keyestudio.com/products/free-shipping-keyestudio-photoresistor-light-dependent-resistor-sensor-module-for-arduino)])"> Link </a> |
| Keyestudio Photoresistors | used for my project to detect nearby obstacles, movement, etc| $4.00 | <a href="(https://www.keyestudio.com/products/keyestudio-ir-infrared-obstacle-avoidance-sensor-module-for-arduino-robot-car)"> Link </a> |


# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
