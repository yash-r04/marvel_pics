## **TASK 1: 3-D printing**

  

3D printing is one of the pioneering technologies of Industry 4.0 enabling rapid development of products. I printed a small and portable mobile stand on the Creality Ender. I learnt about the

*   types of 3D printing (Fused Deposition Modeling (FDM) and resin)
*   type of filament used (PLA used for the model)
*   temperature settings for the bed and nozzle
*   importance of supports for intricate designs
*   infill settings. 

  

In the lab, we use FDM where the filament is loaded into the nozzle head where it is melted to the temperature set by us according to the filament used. The model is printed layer by layer, and the cooling fan ensures that the previous layer is stable enough to withstand the deposition of the next layer.
<br><br>
I downloaded the _stl_ file from the makerworld website, used the creality slicer software to slice the model and get the _gcode_ file that was uploaded to creality cloud for the print
<br>
  
[![3d-print.jpg](https://i.postimg.cc/XJtMTS9X/3d-print.jpg)](https://postimg.cc/7G1Q2Rsy)

  

## **TASK 2: Soldering**

  

Soldering is the process of melting a metal and it’s deposition on the surface of another metal to make a join. One can see tiny silver blobs on the PCBs, where electrical components are held onto the board by the solder.  It’s crucial in the electrical industry as it allows us to  join the components and also allows electrical flow between them.

In the lab, I learnt the basics of soldering - the devices and components(flux, stand) used along with the safety precautions while handling the solder iron.

  

I was given an already soldered wire and led light, I desoldered the joints and resoldered it. I soldered a led onto the pcb.

[![IMG-20240628-WA0023.jpg](https://i.postimg.cc/d1jHjbnz/IMG-20240628-WA0023.jpg)](https://postimg.cc/vgDtQSJz)
  

## **TASK 3:GitHub**

  

Git and Github are one of the most important tools used by developers.

Git is a version control that keeps a track of changes done for a source file, whereas GitHub is an online platform where one can store, share and manage their code, together Git and Github helps a developer to make changes to their code and easily storing it on github.

  

One of the challenges in this task is to navigate through different terminologies that a beginner would easily get confused with so that took a while to understand.

  

I had  GitHub desktop app on my system, so I forked and cloned the repository and rectified the code on VS code, used the source control option to commit the changes and issued a pull request.

[![Screenshot-2024-06-29-173724.png](https://i.postimg.cc/N0dShyWd/Screenshot-2024-06-29-173724.png)](https://postimg.cc/2qB2h5jW)

  

## **TASK 4: API**

  

Application Programming Interface(API) enables two applications that interact with each other and they communicate in the forms of requests and responses.

  

I used Spotify API and accessed it through spotipy library. Through Spotipy, I added OAuth to felicitate authorisation of users by the spotify then get user data such as top artists and tracks. The user can also choose one of the five genres and click on recommended songs to generate a list of songs in that genre that is according to the user's taste. 

The front end is html,css and a little bit of javascript. The back end uses python’s flask framework. I’ve also learnt about virtual environments and got the opportunity to use git for a real life example.

click for code [here](https://github.com/yash-r04/spotify-api)

<iframe width="783" height="440" src="https://www.youtube.com/embed/RlHfSUT_X08" title="linkedin" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

  

## **TASK 5:** **555 A-stable multivibrator**

  

An astable multivibrator is a self-propelled oscillator that continuously switches between two output voltage levels, or states, without input. <br>
In this task we use 555 IC chip and connect to R1=10k ohms and R2 = 22k ohms(approximately 1:2 ratio in resistances) and capacitors. <br><br>
It is a type of relaxation oscillator that produces a square output. The circuit’s output wires were connected to a digital storage oscilloscope(DSO) which showed a duty cycle of 56%.

[![IMG-20240628-WA0006.jpg](https://i.postimg.cc/FRRgBvkS/IMG-20240628-WA0006.jpg)](https://postimg.cc/nsyDX6kV)
[![IMG-20240628-WA0007.jpg](https://i.postimg.cc/KzHrXWtH/IMG-20240628-WA0007.jpg)](https://postimg.cc/wyDsL0fX)
[![IMG-20240628-WA0008.jpg](https://i.postimg.cc/MHf0zYDK/IMG-20240628-WA0008.jpg)](https://postimg.cc/4HZH5Vqr)
  

## **TASK 6: LED toggle with ESP32**

  

ESP32 microcontrollers have a set of General Purpose Input/Output (GPIO) pins that provide a range of functionalities.  


For this task, the connections were made using the breadboard, led lights, resistors(330ohms), jumper wires and ESP32 DEVKIT DOIT, according to the resources given. Using the Arduino IDE, I uploaded the web server code. The web server code consists of the wifi library, network credentials, output state variables(ON,OFF), GPIO pin variables, setup consists code to connect to server and loop consists of html, css code along with client HTTP request.



[![IMG-20240628-WA0010.jpg](https://i.postimg.cc/d36GJtkn/IMG-20240628-WA0010.jpg)](https://postimg.cc/rRdDJT9t)

[![IMG-20240628-WA0011.jpg](https://i.postimg.cc/fbWyhjj4/IMG-20240628-WA0011.jpg)](https://postimg.cc/LJ72tPbv)
  

## **TASK 7: Matplotlib and Pandas**

link to [_code_](https://colab.research.google.com/drive/1wCEgsXjGq80fk2OfAnavuQZBEuCEYpZ4)<br>
[Please note to load the data set into the colab notebook according to the given location in code]

Matplotlib and pandas are very important python libraries used in data science. Matplotlib is used for visualisation and Pandas is used for data manipulation. 

  

I have taken music and mental health dataset from kaggle and visualised the data through pie, line, bar and scatter chart. 

link to [_data set_](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results)

  

The challenge I faced during this task was aggregation of data for the bar graph and pie chart, so used the groupby method to aggregate name of the streaming service as the grouping key and used the count function on within the groupby, and it counts the occurrences of entries in the "Permissions" column \[ permission column was chosen as it was the only column with one value for all groups\] for each streaming service.

  

It was interesting to play around the different values such as line style, alpha values, colours and  subplots. Added titles , xlabel and ylabel and legend in the necessary places.

[![bar-graph.png](https://i.postimg.cc/6QDmsznz/bar-graph.png)](https://postimg.cc/d7jBr2WT)

[![line-graphs.png](https://i.postimg.cc/3NZtb3tg/line-graphs.png)](https://postimg.cc/D48QS3kZ)

[![pie-graph.png](https://i.postimg.cc/0ySSWf59/pie-graph.png)](https://postimg.cc/SnyjjczP)

[![scatter.png](https://i.postimg.cc/tTcCGKDw/scatter.png)](https://postimg.cc/VrjcjHxW)

[![sub-graphs.png](https://i.postimg.cc/23RWrbTs/sub-graphs.png)](https://postimg.cc/SYdRGKBd)
  

##   

## **TASK 8: Command line on Ubuntu**

  

It was interesting to know the history of command lines. Usage of text to interact with programs was a save of resources such as energy and storage. In linux command lines, relative and absolute paths are important and should be used accordingly.

  

>I learnt the basic commands such as:
>1.  pwd - print working directory- prints the directory we are in
2.  cd - change directory
3.  mkdir - makes a new directory
4.  ls - lists the contents in the directory
5.  echo- prints the given argument again. It is used with redirection to create small files
6.  cat- outputs the content of the file name specified, it is only a file viewer.

[![IMG-20240628-WA0020.jpg](https://i.postimg.cc/d06sHPGG/IMG-20240628-WA0020.jpg)](https://postimg.cc/gwwbj7S0)

[![IMG-20240628-WA0016.jpg](https://i.postimg.cc/Zq5nh5bw/IMG-20240628-WA0016.jpg)](https://postimg.cc/75jw3DTz)



##   

## **TASK 9: Thinkercad**

  

Thinkercad is a platform that enables electrical simulations along with other services. <br><br>
I used the platform to simulate a circuit that consists of an ultrasonic sensor that would be mounted on the servo motor so that it creates a radar system, the components would be connected to an arduino board that would in turn be connected to a LCD display to show the distance. The arduino board is uploaded with a simple code for it to work.

[![Screenshot-2024-06-02-175313.png](https://i.postimg.cc/ZY13mpy0/Screenshot-2024-06-02-175313.png)](https://postimg.cc/Jt5tcyxW)

[![Screenshot-2024-06-02-175342.png](https://i.postimg.cc/ZK7G0Y49/Screenshot-2024-06-02-175342.png)](https://postimg.cc/0bSWBs6x)

##   

## **TASK 10: Speed Control of DC motor**

  

Followed the given resource and made the circuit accordingly. Uploaded the code into the Arduino using Arduino IDE. This simple circuit could be used to create self-driving robots and one can find a similar mechanism in ceiling fans.
The l298 is Dual H-Bridge motor driver  allows speed and direction control of two DC motors at the same time.

[![IMG-20240628-WA0014.jpg](https://i.postimg.cc/TwmptHYx/IMG-20240628-WA0014.jpg)](https://postimg.cc/mzLLDjHp)

  

  

## **TASK 11: Portfolio website**

  

### click here for [**my portfolio website !**](https://yash-r04.github.io/portfolio/)

I have used HTML, CSS and little javascript.

It is responsive and shows my contact details, skills and project works!

  

## **Task 12: Active participation**

  

I participated and followed up the course of "Coding and programing" by Samsung Innovation Campus conducted in our college. I got to participate in the hackathon and contributed as a backend developer to the project!

[![samsung.jpg](https://i.postimg.cc/RFw2qMht/samsung.jpg)](https://postimg.cc/G8hX5nk3)
  

## **Task 13: Kaggle - Titanic Competition**

participated in the Titanic ML survivor prediction competation. The data was cleaned to a larger extent and the prediction rate can be improved by focusing on the finer details (such as surnames, age).

[![Screenshot-2024-07-21-032028.png](https://i.postimg.cc/0j128gDX/Screenshot-2024-07-21-032028.png)](https://postimg.cc/TLQX94kn)

## **Task 14: Markdown**

Learnt the syntax for markdown and learnt the perks of using it.

[![Screenshot-2024-07-21-013558.png](https://i.postimg.cc/3JggBhKt/Screenshot-2024-07-21-013558.png)](https://postimg.cc/kBg6JkRS)
