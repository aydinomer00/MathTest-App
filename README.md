# MathTest-App

Explanation
MathTest-App is an iOS application with a simple interface that I developed to reinforce my newly learned Swift skills. It is designed for users who want to practice mathematics and improve their quick thinking skills.

Setup
To copy the project to your own development environment, clone it from the GitHub repo. All asset files and necessary source codes are included. After opening it in Xcode, you can run it in the simulator or install it on an 

iOS device.
Use
The application is based on solving the math questions you encounter during the 30-second tour. You can use the TRUE and FALSE buttons on the screen to answer the questions correctly or incorrectly. Each correct answer earns you points.

Technologies and Libraries Used
UIKit: UIKit framework was used to create the interface of the application.
AVFoundation: AVFoundation was used for background music and sound effects.
AudioToolbox: AudioToolbox framework was preferred to use system sounds in user interactions.
Functions and Methods
playSound(): Used to start music that plays continuously in the background.
playEffectSound(): Used to play sound effects when buttons are clicked.
updateTimer(): This is the timer function used to update the quiz duration.
updateUI(): Adjusts the user interface according to the current question and answer status.
loadQuestionsFromFile(): Loads questions and answers from a file and displays them on the screen.
restartQuiz(): Allows the user to restart the game and resets the timer.
