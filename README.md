# Friday-robot
Friday is an AI Assistant which uses machine learning, currently friday works on manually installed data but it has ability to understand feeling of the command given, it categorises it into happy, sad, etc. It is integrated with a robot which can see, speak, and interact with real world all done through precise movements, and other advanced boards like raspberry pi and Arduino. To control this I made an app from scratch personalized for friday. On the app we can see the robot's pov as shown in the video. Friday can be controlled through its app as well as via voice. It comes with collision prevention system which prevents it from colliding in walls when given wrong command or forcefully colliding it in wall.

Features:
1. Machine learning integration
2. Speech recognition
3. Automated Collision Prevention
4. Bluetooth controlled via personalized app as well as voice based control
5. Answers factual questions
6. Greeting gesture on conversing to friday
7. Wake-word detection - "Friday"
8. Google/Wikipedia search through voice commands
9. Current date and time
10. Weather and temperature information
11. Natural voice synthesis using Google Text-to-Speech
12. Latest news updates of all genres
13. COVID statistics lookup
14. Recipe search and cooking instructions
15. System volume control
16. Battery percentage announcement
17. Random motivational quotes
18. Random fun facts
19. Joke generation
20. Rock–Paper–Scissors game
21. Coin toss
22. Voice repeat mode
23. Personalized greetings
24. Emotional/supportive responses
25. Appreciation and gratitude responses
26. Independent arms movement
27. Full neck rotation
28. Real-time battery monitor

Software Technologies Used:
1. Python - modules such as: PyTorch, NumPy, NLTK (Natural Language Toolkit), Speechrecognition
2. Arduino (C/C++)
3. Webscraping
4. APIs such as: Wikipedia API, OpenWeatherMap API, Google News, Quotable API, Useless Facts API, WikiHow API

Hardware Technologies Used:
1. Raspberry Pi
2. Arduino UNO
3. High torque motors
4. Motor driver
5. IR sensors
6. Speakers
7. Mic
8. ESP32 cam
9. battery monitor
10. 18650 battery
11. 12v Lithium battery
12. Bread board

Theoritical Documentation:
1. Problem Statement: I asked a simple question, can I my friday (AI ASSISTANT) interact with real world? the came yes. After that I started designing the robot, built hardware, combined motor driver with Arduino and as soon as I combined Arduino and Raspberry PI my dream came true. Now Friday was interacting with real world. This opened limitless possibilities because my Friday was not bound to my PC it was now installed in the robot and can move to anywhere.
2. Inspiration: The inspiration to build Friday came to me as a kid watching Iron man movies, at that time I didn't had enough knowledge to build one but I started learning and finally built my own Friday.

Challenges:
1. I did not have any knowledge of building apps. Therefore, I first spent time learning it and then finally I built one on my own, apk file is availble to download and test the app by yourself.
2. Installing friday on raspberry pi : installing it on rpi was a huge challenge and a game changer, it took me months just to make friday's code run still it couldn't perform any action, it was a massive challenge to install modules in rpi  and i had to rebuild my text to speech system because old version didn't support in rpi, after that mic was not working on rpi zero so i had to buy rpi 3 and redo everything which cost me a lot of money as well as time.
3. Achieving reliable speech recognition in noisy environments: I spent another month trying to figure out how to make speech recognition accurate because normal environment is noisy but after spending time i finally figured that out, i just had to restrict the duration for which it listens and resets to listening again, i posted a video of this solution on my yt channel: https://www.youtube.com/watch?v=C2EwddWVKmg
4. Reducing response latency: This was an alarming issue because it was taking a lot of time to respond to basic questions, but the fix was easy. I just had to distribute my code into different files thats why you can see there are so many files this makes code run faster.
5. Collision prevention system: i had to change the whole hardware of base of the robot and had to install 2 IR sensors, one in front another in back and had to manipulate my Arduino code, but it did not work. The sensor was working but robot was still not stopping which took me days to figure out why. The fix was simple i had to create a separate function for stopping wheels and combine it with sensors.
6. Absence of 3D printer: I felt need of 3D printer to print custom part which would make hardware more clean and stable, im looking forward to utilise university's labs to gain knowledge and use 3D printers.

Future Improvements:
1. Face recognition: I have already cracked code for facial recognition, also i have tried and tested it I just have to put the block of code in main file and add images to recoznise face.
2. Object detection using computer vision: by using opencv module i can use computer vision but currently i have to study object detection and therefore it will take some time to bring it in application.
3. Gesture recognition: using opencv i was to add certain gestures such as hand waving etc to which it also reacts as hand waving
4. Autonomous navigation with obstacle avoidance: this is an advanced feature which i want to add into my robot but this requires me to attain knowledge of mapping, opencv, etc. for which i need guidance and good mentorship.
5. Chat memory and personalized interactions: this feature will change how robot interacts with others because it will be able to remember personal information from face of specific person and respond accordingly.
6. Controlling TV with robot: currently im working on this, theoritically i have figured out everything and how things will be done. With voice command it will be able to turn on TV and play all channels as per my need.
7. Cloud synchronization: I want to create a system  which uses camera of robot that detects threat and alarming situations and starts recording automatically of that situation and saves it to cloud to use it as proof and send it to appropriate authorities for safety.
8. Adding more movement to arms and legs: currently elbow joint and knee joint is not working as it requires acctuator to function which is expensive to this idea is at pause for sometime. 

https://github.com/user-attachments/assets/3fb2aea5-e808-4ce8-a756-d593208af6f1

